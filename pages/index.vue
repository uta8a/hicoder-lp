<template>
  <div>
    <div id="main-op" @animationend="$router.push('/home')">HiCoder</div>
  </div>
</template>

<script>
</script>

<style scoped>
#main-op {
  animation: show 1s ease 0s forwards;
}
@keyframes show {
  0% {opacity: 0%;}
  100% {opacity: 100%;}
}
</style>
