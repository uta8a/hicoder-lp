<template>
  <section id="top" class="section is-paddingless">
    <div id="top-content" class="is-paddingless">
      <div class="textbox">
        <div class="inner title main-title">HiCoder</div>
        <div class="inner title">次回開催は未定です</div>
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
@media (max-width: 767px) {  
  .main-title {
    font-size: 4rem;
  }
}

@media (min-width: 768px) {
  .main-title {
    font-size: 10rem;
  }
}
.main-title {
  font-weight: bold;
}
</style>