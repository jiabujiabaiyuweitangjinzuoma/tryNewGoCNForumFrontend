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
        <forum-header></forum-header>
        <container-wrap></container-wrap>
        <common-list></common-list>

    </div>




</template>

<!--行为-->
<script>

    import ForumHeader from '../components/ForumHeader'
    import ContainerWrap from '../components/ContainerWrap'
    import CommonList from '../components/CommonList'

    export default {
        name: 'home',
        components: {
            ForumHeader,
            ContainerWrap,
            CommonList,

        }
    }
</script>

<style>



</style>
