<template>
  <div>
    <Nav></Nav>
      <div class="container">
        <nuxt />
      </div>
  </div>
</template>

<script>
import Nav from '~/components/Nav'
export default {
  components: {
    Nav
  },
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
<style>
html {
  margin-top: 3.25rem;
}
body {
  margin-top: -3.25rem;
}
.columns:last-child {
    margin-bottom: 0;
    padding-bottom: 0;
}
</style>