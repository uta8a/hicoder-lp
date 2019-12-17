<template>
  <div>
    <div id="main-op" class="notification is-success is-paddingless is-marginless" 
    @animationend="$router.push('/home')"
    >HiCoder</div>
    <div id="wrap" class="is-clipped">
      <div id="one" class="half"></div>
      <div id="two" class="half"></div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>
#main-op {
  position: absolute;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  animation: show 1s ease 0s forwards;
}
.half {
  position: inherit;
  width: 100%;
  height: 50%;
  background: #000;
}
#wrap {
  top: 0;
  height: 100vh;
}
#one {
  top: 0;
  animation: down 0.5s ease 0s forwards,up 0.5s ease 0.5s forwards;
}
#two {
  top: 0;
  animation: up-2 0.5s ease 0s forwards,down-2 0.5s ease 0.5s forwards;
}
@keyframes show {
  0% {opacity: 0%;}
  100% {opacity: 100%;}
}
@keyframes down {
  from {transform: translateY(-100%);}
  to {transform: translateY(0%);}
}
@keyframes up {
  from {transform: translateY(0%);}
  to {transform: translateY(-100%);}  
}
@keyframes down-2 {
  from {transform: translateY(0%);}
  to {transform: translateY(100%);}
}
@keyframes up-2 {
  from {transform: translateY(100%);}
  to {transform: translateY(0%);}  
}
</style>
