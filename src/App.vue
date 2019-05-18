<template>
    <div id="app">
        <forum-header></forum-header>

        <!-- <img src="./assets/logo.png">-->
        <HelloWorld/>
    </div>
</template>

<script>
    import ForumHeader from './components/Header'
    import ForumFooter from './components/Footer'
    import HelloWorld from './components/HelloWorld'

    export default {
        name: 'App',
        components: {
            ForumHeader,
            ForumFooter,
            HelloWorld
        }
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
