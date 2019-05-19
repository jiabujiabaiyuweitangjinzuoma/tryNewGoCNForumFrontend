<template>

    <div class="forum-header">

      <div>
          <form class="aw-search-box">
              <input type="text" placeholder="搜索话题/问题/人"/>

          </form>
      </div>

        <ul class="aw-nav">
            <li>
                <a href="find-page">发现</a>

            </li>
            <li>
                <a href="download">下载</a>

            </li>

        </ul>

        <ul class="aw-user-nav">
            <li>
                <a href="register">注册</a>

            </li>
            <li>
                <a href="login">登录</a>

            </li>


        </ul>

    </div>


</template>

<script>
    export default {
        name: 'forum-header',
    }


</script>


<style scoped>

    .forum-header {
    /*    display: flex;*/

        width: 1110px;
        height: 52px;
        margin-top: -60px;
        background-color: #499ef3;
    }


    ul {
        display: inline-block;
    }
    li {
        display: inline-block;
    }

    a {
        text-decoration: none /*删除a下划线*/
    }

    li{
        list-style: none;
    }


</style>
