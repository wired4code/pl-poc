<template>
	<header class='header-container'>
        <div class='header-logo'>
            <img src='../assets/logo.png' alt=''>
        </div>
        <search></search>
        <volume-control></volume-control>
    </header>
</template>

<script>
import Search from './Search.vue'
import Volume from './Volume.vue'
export default {
  name: 'header-container',
  components: {
    'search': Search,
    'volume-control': Volume
  },
  data () {
    return {
      msg: 'Playlist Header Goes Here'
    }
  }
}
</script>

<style scoped>
  .header-container {
    height: 90px;
    background-color: black;
    color: #fff;
  }

  .header-logo {
      float: left;
      padding: 15px 0 0 15px;

  }
</style>
