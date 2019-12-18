<template>
  <div>
    <Nav></Nav>
    <div>
      <Top></Top>
      <About></About>
      <News></News>
      <Contact></Contact>
    </div>
  </div>
</template>

<script>
import Top from "~/components/Top";
import About from "~/components/About";
import News from "~/components/News";
import Contact from "~/components/Contact";
import Nav from "~/components/Nav";
export default {
  components: {
    Top,
    About,
    News,
    Contact,
    Nav
  }
};
</script>
<style>
.textbox {
  color: white;
  font-size: 2.5rem;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 80%;
}
.title {
  text-align: center;
  color: white;
  font-size: 3.5rem;
  font-weight: bold;
}
a {
  color: white;
}
</style>