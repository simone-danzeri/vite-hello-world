<!-- JS -->
<script>
    export default {
        name: 'AppHero'
    }
</script>
<!-- JS -->
<!-- HTML -->
<template>
    <div id="jumbotron">
        <h3>Il mio primo Jumbotron con Vite!</h3>
        <div class="container">
            <img src="../assets/vue.svg" alt="Vue logo">
        </div>
    </div>
</template>
<!-- HTML -->

<!-- CSS -->
<style scoped>
    h3{
        text-align: center;
    }
    .container{
        margin: 0 auto;
        display: flex;
        justify-content: center;
        background-color: antiquewhite;
        max-width: 80%;
        padding: 30px 0;
    }
    .container img{
        display: block;
        width: 250px;
    }
</style>
<!-- CSS -->