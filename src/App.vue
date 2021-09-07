<template>
  <div class="app">
    <Header />
    <router-view></router-view>
    <home />
    <Footer />
  </div>
</template>



<script>
import home from "./components/home.vue";
import Header from "./components/header.vue";
import Footer from "./components/footer.vue";
export default {
  name: "App",
  components: {
    home,
    Header,
    Footer,
  },
};
</script>



<style>
</style>
