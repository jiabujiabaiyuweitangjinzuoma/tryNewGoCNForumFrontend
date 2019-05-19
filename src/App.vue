<template>
    <div id="app">
        <home></home>

        <!--        <HelloWorld/>-->
    </div>
</template>

<script>
    import ForumHeader from './components/Header'
    import ForumFooter from './components/Footer'
    import TopMenu from './components/TopMenu'
    import NavTab from './components/NavTab'
    import Home from "./components/Home";

    export default {
        name: 'App',
        data: function () {
            return {}
        },
        components: {
            Home,
            ForumHeader,
            ForumFooter,
            TopMenu,
            NavTab
        },
        created() {
            let logoImg = "assets/logo.png";

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
