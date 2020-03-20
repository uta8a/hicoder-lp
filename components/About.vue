<template>
  <section id="about" class="section is-paddingless">
    <div id="about-content" class="is-paddingless">
      <div class="textbox">
        <div class="inner title">About</div>
        <div class="inner">HiCoderは、広島大学のコンピュータが好きな学生の集まりです。個人の活動がメインで、たまに集まってIT系の話をして楽しんでいます。</div>
        <div
          class="inner"
        >また、グループで大会に出ることもあります。今までに、大学対抗の競技プログラミング大会であるICPCや、インフラに関する知識を競うICTSCなどに参加しています。</div>
      </div>
    </div>
  </section>
</template>

<style scoped>
#about {
  height: calc(100vh - 3.25rem);
}
#about-content {
  height: 100%;
  position: relative;
  background: linear-gradient(
      90deg,
      rgba(255, 98, 143, 0.75),
      rgba(0, 212, 255, 0.75)
    ),
    url(~assets/my-photo-3.webp);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
</style>