<template>
	<header class='header-container'>
        <div class='header-logo'>
            <img src='../assets/logo.png' alt=''>
        </div>
        <search></search>
        <volume-control></volume-control>
        <div class="video-control-container">
            <button id="skip" class="video-controls">Skip</button>
            <button id="sync" class="video-controls">Sync</button>
        </div>
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

    }
  }
}
</script>

<style scoped>
  .header-container {
    height: 90px;
    display: flex;
    flex-wrap: nowrap;
    background-color: black;
    color: #fff;
    flex-direction: row;
    justify-content: space-evenly;
  }

  .header-logo {
      padding: 15px 0 0 15px;
      flex-direction: column;
  }

  .video-control-container {
      flex-direction: column;
  }

  .video-controls {
      background-color: #000;
      color: #fff;
      border: none;
      font-size: 15px;
      font-weight: 800;
      padding-top: 15px;
  }

  .video-controls:hover {
      color: red;
      cursor: pointer;
  }

</style>
