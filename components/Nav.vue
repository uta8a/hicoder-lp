<template>
  <nav
    class="navbar header"
    role="navigation"
    aria-label="main navigation"
    style="position: -webkit-sticky;position:sticky;top:0"
  >
    <div class="navbar-brand">
      <a class="navbar-item" href="/home">
        <img src="~assets/hicoder.png" alt="HiCoder" height="3rem" />
      </a>
    </div>
    <div id="menubar" class="navbar-menu">
      <div class="navbar-end">
        <nuxt-link class="navbar-item" v-scroll-to="'#top'" to>Top</nuxt-link>
        <nuxt-link class="navbar-item" v-scroll-to="'#about'" to>About</nuxt-link>
        <nuxt-link class="navbar-item" v-scroll-to="'#news'" to>News</nuxt-link>
        <nuxt-link class="navbar-item" v-scroll-to="'#contact'" to>Contact</nuxt-link>
      </div>
    </div>
  </nav>
</template>
<style scoped>
nav {
  background: linear-gradient(
      90deg,
      rgb(253, 18, 1),
      rgb(55, 0, 255)
    );
}
</style>