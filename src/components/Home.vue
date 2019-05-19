<!--模板-->
<template>
    <div id="home">

<!--        整理首页内容
    1 导航栏    nva        原来叫top-menu
    2 高层菜单  category-menu
    3 发现页    find-page
    4 侧边栏  热门用户和热门文章 hot-topics

    5 页脚
-->
        <forum-header> 导航栏</forum-header>

<!--        <top-menu>每日新闻4个</top-menu>-->


<!--        <nav-tab>发现</nav-tab>-->
<!--    <card-item-wrap></card-item-wrap>-->
<!--        <side-bar> 侧边-热门文章</side-bar>-->

<!--        <forum-footer></forum-footer>-->
    </div>
    <!--  <p> hello</p>-->
</template>

<!--行为-->
<script>

    import ForumHeader from './Header'
    import ForumFooter from './Footer'
    import CardList from './CardList'
    // import CardDetail from './CardDetail'
    import TopMenu from './TopMenu'
    import NavTab from './NavTab'
    import SideBar from './SideBar'

    export default {
        name: 'home',
        components: {
            ForumHeader,
            ForumFooter,
            TopMenu,
            NavTab,
            SideBar,
            CardList

        }
    }
</script>

<style>

</style>
