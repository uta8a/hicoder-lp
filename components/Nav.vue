<template>
  <nav
    class="navbar header has-shadow is-primary"
    role="navigation"
    aria-label="main navigation"
    style="position:sticky;top:0"
  >
    <div class="navbar-brand">
      <a class="navbar-item" href="/home">
        <img src="~assets/hicoder.png" alt="HiCoder" height="2em" />
      </a>
    </div>
    <div id="menubar" class="navbar-menu">
      <div class="navbar-end">
        <nuxt-link class="navbar-item" data-target="a" v-scroll-to="'#top'" to>Top</nuxt-link>
        <nuxt-link class="navbar-item" data-target="b" v-scroll-to="'#about'" to>About</nuxt-link>
        <nuxt-link class="navbar-item" data-target="c" v-scroll-to="'#news'" to>News</nuxt-link>
        <nuxt-link class="navbar-item" data-target="c" v-scroll-to="'#contact'" to>Contact</nuxt-link>
      </div>
    </div>
  </nav>
</template>