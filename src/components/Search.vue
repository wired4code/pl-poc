<template>
    <div class="search-container">
      <input class='search-form' type='search' placeholder='Add videos to your playlist ...'>
      <input type='image' src='../assets/search.png'>
      <a href=""><img src='../assets/search.png' alt=''></a>
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

    /* clears the placeholder text when input is focused */
    input:focus::-webkit-input-placeholder { color:transparent; }
    input:focus:-moz-placeholder { color:transparent; } /* FF 4-18 */
    input:focus::-moz-placeholder { color:transparent; } /* FF 19+ */
    input:focus:-ms-input-placeholder { color:transparent; } /* IE 10+ */

    .search-container {
        display: table-cell;
        position: relative;
    }

    img {
        position: absolute;
        top: 34px;
        left: 30px;
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
        padding-left: 30px;
        margin-left: 30px;
        float: left;
        background-color: #616573;
        font-size: 15px;
        opacity: 0.7;
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



