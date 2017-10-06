<template>
    <div class="volume-container">
      <input class="volume-control" type="range" min ="0" max="100" step="1" value="50">
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

    .volume-container {
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    .volume-control {
        outline: none;
        padding: 0;
        width: 140px;
        height: 6px;
        background-color: #616573;
        background-image: -webkit-gradient(linear, 50% 0%, 50% 100%, color-stop(0%, #473e4f), color-stop(100%, #51475a));
        background-image: -webkit-linear-gradient(#473e4f, #51475a);
        background-image: -moz-linear-gradient(#473e4f, #51475a);
        background-image: -o-linear-gradient(#473e4f, #51475a);
        background-image: linear-gradient(#AC0809, #AC0809);
        background-size: 50% 100%;
        background-repeat: no-repeat;
        border-radius: 10px;
        cursor: pointer;
        -webkit-appearance: none;
    }

</style>



