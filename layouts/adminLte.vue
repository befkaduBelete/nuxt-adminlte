<template>
  <div class="wrapper">
    <NavBar />
    <SideBar />
    <nuxt />
    <Footer />
  </div>
</template>

<script>
import NavBar from "../components/pages/NavBar";
import SideBar from "../components/pages/SideBar";
import Footer from "../components/pages/Footer";
export default {
  components: {
    NavBar,
    SideBar,
    Footer,
  },
};
</script>
