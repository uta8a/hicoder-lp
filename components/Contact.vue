<template>
  <section id="contact" class="section is-paddingless">
    <div id="contact-content" class="is-paddingless">
      <div class="textbox">
        <div class="inner title">Contact</div>
        <div class="inner">連絡はメールアドレスまたはTwitterへお願いします</div>
        <div class="inner">TwitterのDMは開放しています</div>
        <div class="inner">mail: huhicoder[at]gmail.com</div>
        <div class="inner">
          Twitter:
          <a
            href="https://twitter.com/huhicoder"
            style="text-decoration:none"
          >@huhicoder</a>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
#contact {
  height: calc(100vh - 3.25rem);
}
#contact-content {
  height: 100%;
  position: relative;
  background: linear-gradient(
      45deg,
      rgba(246, 255, 0, 0.75),
      rgba(255, 0, 161, 0.75)
    ),
    url(~assets/my-photo-1.webp);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.textbox {
  text-align: center;
}
</style>