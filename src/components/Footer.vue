<template>
  <footer>
    <p>footer</p>
  </footer>
</template>

<script>
  export default {
    name: 'forum-footer',  // 这里是自定义标签
    props:{
      footerTitle:{
        type:String
      }
    },
    // data() {
    //   return {
    //     copyright: "Copyright 2018 demo"
    //   }
    // }
  }
</script>


<!--scoped 作用域-->
<style scoped>

  /* header {
    background-color: #222;
    padding: 10px;
  }

footer  p {
    color: lightgreen;
    text-align: center;
  } */
</style>
