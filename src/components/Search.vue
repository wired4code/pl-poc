<template>
    <div class="search-container">
      <input class="search-form" type="search" placeholder="Find videos to add to your playlist ...">
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

    input[type=search]::-ms-clear {  display: none; width : 0; height: 0; }
    input[type=search]::-ms-reveal {  display: none; width : 0; height: 0; }

    /* clears the 'X' from Chrome */
    input[type="search"]::-webkit-search-decoration,
    input[type="search"]::-webkit-search-cancel-button,
    input[type="search"]::-webkit-search-results-button,
    input[type="search"]::-webkit-search-results-decoration { display: none; }

    .search-container {
        float: left;
    }

    .search-form {
        height: 35px;
        width: calc(100vw - 400px);
        min-width: 200px;
        margin-top: 30px;
        border-radius: 10px;
        color: #fff;
        border: none;
        outline: none;
        padding-left: 10px;
        margin-left: 30px;
        float: left;
        background-color: #616573;
        font-size: 15px;
    }

    ::-webkit-input-placeholder { /* Chrome/Opera/Safari */
        color: white;
    }
    ::-moz-placeholder { /* Firefox 19+ */
        color: white;
    }
    :-ms-input-placeholder { /* IE 10+ */
        color: white;
    }
    :-moz-placeholder { /* Firefox 18- */
        color: white;
    }

</style>



