<template>
  <div>
    <Header />
    <Menu />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header";
import Menu from "../components/Menu";
import Footer from "../components/Footer";

export default {
  name: "MainLayouts",
  components: {
    Header,
    Menu,
    Footer
  }
};
</script>
