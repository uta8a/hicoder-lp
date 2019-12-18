<template>
  <section id="news" class="section is-paddingless">
    <div id="news-content" class="is-paddingless">
      <div class="textbox">
        <div class="inner title">News</div>
        <div class="inner">ここは自動でYAMLからgenerateして上位何件とってくるとかしたい</div>
      </div>
    </div>
  </section>
</template>

<style scoped>
#news {
  height: calc(100vh - 3.25rem);
}
#news-content {
  height: 100%;
  position: relative;
  background: linear-gradient(
      -135deg,
      rgba(0, 255, 0, 0.75),
      rgba(255, 0, 255, 0.75)
    ),
    url(~assets/my-photo-2.jpeg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
</style>