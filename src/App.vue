<template>
<div class="app">
<header />

<router-view></router-view>


  <home />

<footer />

</div>
</template>

<script>
import home from './components/home.vue'
import header from './components/header.vue'
import footer from './components/footer.vue'
export default {
  name: 'App',
  components: {
    home,
    header,
    footer
  }
}
</script>



<style>


</style>
