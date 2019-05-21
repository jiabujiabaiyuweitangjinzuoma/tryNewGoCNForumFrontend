<template>
    <div id="forum-header" class="aw-top-menu-wrap">

        <b-navbar toggleable="lg" type="dark" variant="info">
            <b-navbar-brand href="#">GoCN Forum</b-navbar-brand>
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>
                    <b-nav-item href="#">首页</b-nav-item>
                    <b-nav-item href="#">下载</b-nav-item>
                    <b-nav-item-dropdown text="每日新闻" right>
                        <b-dropdown-item href="#">每日新闻</b-dropdown-item>
                        <b-dropdown-item href="#">有问必答</b-dropdown-item>
                        <b-dropdown-item href="#">文章分享</b-dropdown-item>
                        <b-dropdown-item href="#">招聘信息</b-dropdown-item>
                    </b-nav-item-dropdown>
                </b-navbar-nav>


                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto">
                    <b-nav-form>
                        <b-form-input size="sm" class="mr-sm-2" placeholder="搜索问题/话题/人"></b-form-input>
                        <b-button size="sm" class="my-2 my-sm-0" type="submit">搜索</b-button>
                    </b-nav-form>

                    <b-navbar-nav  right>
                        <!-- Using 'button-content' slot -->
                        <template slot="button-content"><em>User</em></template>
                        <b-nav-item href="#">登录</b-nav-item>
                        <b-nav-item href="#">注册</b-nav-item>
                    </b-navbar-nav>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>

</template>

<script>
    export default {
        name: "ForumHeader"
    }
</script>

<style scoped>


</style>