<template>
<div class="home-component">
<header />
<p>Home</p>
<footer />
</div>
</template>

<script>
import header from './header.vue'
import footer from './footer.vue'
export default {
  name: 'home',
  Comments:{
      header,
      footer
  },
  props: {
    msg: String
  }
}
</script>


<style>
</style>
