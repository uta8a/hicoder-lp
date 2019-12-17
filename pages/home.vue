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