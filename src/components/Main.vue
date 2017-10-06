<template>
  <div class="box">
	  <header-container></header-container>
    <body-container></body-container>
  </div>
</template>

<script>
import Header from './Header.vue'
import Body from './Body.vue'
export default {
  name: 'main',
  components: {
    'header-container': Header,
    'body-container': Body
  },
  data () {
    return {
      msg: 'Welcome to the Main View'
    }
  }
}
</script>

<style>
  .box {
    height: 100vh;
  }

</style>
