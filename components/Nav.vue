<template>
  <nav
    class="navbar header has-shadow is-primary"
    role="navigation"
    aria-label="main navigation"
    style="position:sticky;top:0"
  >
    <div class="navbar-brand">
      <a class="navbar-item" href="/">
        <img src="~assets/buefy.png" alt="Buefy" height="2em" />
      </a>
    </div>
    <div id="menubar" class="navbar-menu">
      <div class="navbar-end">
        <nuxt-link class="navbar-item" data-target="a" v-scroll-to="'#a'" to>Section A</nuxt-link>
        <nuxt-link class="navbar-item" data-target="b" v-scroll-to="'#b'" to>Section B</nuxt-link>
        <nuxt-link class="navbar-item" data-target="c" v-scroll-to="'#c'" to>Section C</nuxt-link>
      </div>
    </div>
  </nav>
</template>