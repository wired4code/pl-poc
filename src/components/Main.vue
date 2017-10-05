<template>
	<header-container></header-container>
</template>

<script>
import Header from './Header.vue'
export default {
  name: 'main',
  components: {
    'header-container': Header
  },
  data () {
    return {
      msg: 'Welcome to the Main View'
    }
  }
}
</script>

<style>
  .main-container {
    height: 90px;
    background-color: black;
    opacity: 0.8;
  }
</style>
