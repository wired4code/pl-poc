<template>
    <div class="container">
        <div class="video-box"></div>
        <div class="message-box"></div>
    </div>
</template>

<script>

export default {
  name: 'body-container',
  components: {

  },
  data () {
    return {

    }
  }
}
</script>

<style scoped>
    .container {
        display: flex;
        flex-wrap: nowrap;
        height: calc(100% - 90px);
        background-color: green;
        justify-content: flex-start;
    }

    .video-box {
        flex-direction: column;
        flex-grow: 4;
        height: 100%;
        background-color: orange;
    }

    .message-box {
        flex-direction: column;
        flex-grow: 1;
        height: 100%;
        background-color: yellow;
    }

</style>
