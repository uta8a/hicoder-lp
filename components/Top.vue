<template>
  <section id="top" class="section is-paddingless">
    <div id="top-content" class="is-paddingless">
      <div class="textbox">
        <div class="inner title main-title">HiCoder</div>
      </div>
    </div>
  </section>
</template>

<style scoped>
#top {
  height: calc(100vh - 3.25rem);
}
#top-content {
  height: 100%;
  position: relative;
  background: linear-gradient(
      90deg,
      rgba(6, 28, 224, 0.568),
      rgba(18, 197, 182, 0.87)
    ),
    url(~assets/my-photo-4.jpeg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.main-title {
  font-size: 10rem;
  font-weight: bold;
}
</style>