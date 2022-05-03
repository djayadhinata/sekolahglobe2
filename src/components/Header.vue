<template>
  <nav
    class="navbar navbar-expand-md navbar-dark fixed-top bg-dark"
    style="border-top: 5px solid #0d106e;"
  >
    <div class="container-fluid">
      <router-link :to="{ name: 'home' }" class="navbar-brand">
        SMKS Globe 2</router-link
      >
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarCollapse"
        aria-controls="navbarCollapse"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav mr-auto mb-2 mb-md-0">
          <li class="nav-item">
            <router-link :to="{ name: 'post' }" class="nav-link">
              BERITA</router-link
            >
          </li>
          <li class="nav-item">
            <router-link :to="{ name: 'event' }" class="nav-link">
              AGENDA</router-link
            >
          </li>
          <li class="nav-item">
            <router-link :to="{ name: 'photo' }" class="nav-link">
              GALERI</router-link
            >
          </li>
          <li class="nav-item">
            <router-link :to="{ name: 'video' }" class="nav-link">
              VIDEO</router-link
            >
          </li>
          <li class="nav-item">
            <router-link :to="{ name: 'contact' }" class="nav-link">
              KONTAK</router-link
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Header",
};
</script>
