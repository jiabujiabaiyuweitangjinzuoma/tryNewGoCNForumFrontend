<template>


  <div class="top-menu">
    每日新闻等
  </div>

</template>

<script>
  export default {
    name: 'top-menu',
    // props: {
    //   headerTitle: {
    //     type: String
    //   }
    // },
    // data() {
    //   return {
    //     title: " demo header"
    //   }
    // },
    // methods: {
    //   changeTitle: function () {
    //     // this.headerTitle = "header title changed, not footer header";
    //     this.$emit("titleChanged", "这是参数: 子组件使用emit通过注册方法向父组件传值")
    //   }
    // }
  }
</script>


<!--scoped 作用域-->
<style scoped>

  *{
    box-sizing: border-box;
  }
  dl dt img{
    width: 50px;
    height: 50px;
  }
  dt dl dd {
    float: left;
  }

  dt {
    display: block;
  }

  body, input, button, select, textarea, h1, h2, h3, h4, h5, h6 {
    font-family: 'Helvetica Neue', 'STHeiti', '微软雅黑', 'Microsoft YaHei', Helvetica,Arial,sans-serif;
  }

</style>
