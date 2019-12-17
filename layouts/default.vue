<template>
  <div>
    <nav class="navbar header has-shadow is-primary is-fixed-top"  role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="/">
          <img src="~assets/buefy.png" alt="Buefy" height="28" />
        </a>
      </div>
      <div id="menubar" class="navbar-menu">
        <div class="navbar-end">
          <a class="navbar-item" href="#a" data-target="a">Section A</a>
          <a class="navbar-item" href="#b" data-target="b">Section B</a>
          <a class="navbar-item" href="#c" data-target="c">Section C</a>
        </div>
      </div>
    </nav>

    <section class="main-content columns is-fixed-top">
      <aside class="column is-2 section">
        <p class="menu-label is-hidden-touch">General</p>
        <ul class="menu-list">
          <li v-for="(item, key) of items" :key="key">
            <nuxt-link :to="item.to" exact-active-class="is-active">
              <b-icon :icon="item.icon" />
              {{ item.title }}
            </nuxt-link>
          </li>
        </ul>
      </aside>

      <div class="container column is-10">
        <nuxt />
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          title: "Home",
          icon: "home",
          to: { name: "index" }
        },
        {
          title: "Inspire",
          icon: "lightbulb",
          to: { name: "inspire" }
        }
      ]
    };
  }
};
</script>
