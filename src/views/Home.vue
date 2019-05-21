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

    <b-container class="bv-example-row">
      <b-row>
        <b-col sm="8">
          <container-wrap></container-wrap>
          <common-list></common-list>
        </b-col>
        <b-col sm="4">
            <side-bar> </side-bar>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<!--行为-->
<script>
import ForumHeader from "../components/ForumHeader";
import ContainerWrap from "../components/ContainerWrap";
import CommonList from "../components/CommonList";
import SideBar from "../components/SideBar";

export default {
  name: "home",
  components: {
    ForumHeader,
    ContainerWrap,
    CommonList,
    SideBar
  }
};
</script>

<style>
</style>
