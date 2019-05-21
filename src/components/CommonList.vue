<template>
  <div id="common-list">
    <ul>
      <li>
        <!-- li中放两个div 图和内容               -->
        <div class="aw-item" >
          <!-- 图片 -->
          <div class="item-img">
            <a
              class="aw-user-name hidden-xs"
              data-id="922"
              href="https://gocn.vip/people/easyhacking"
              rel="nofollow"
            >
              <img src="https://gocn.vip/uploads/avatar/000/00/09/22_avatar_max.jpg" alt>
            </a>
          </div>
          <div class="aw-question-content">
            <p class="title">
              <a href="https://gocn.vip/question/3344">GoCN每日新闻(2019-05-21)</a>
            </p>
            <a class="pull-right text-color-999" href="https://gocn.vip/question/3344#!answer_form">回复</a>

            <p>
              <a href="https://gocn.vip/people/easyhacking" class="aw-user-name">EasyHacking</a>
              <span class="text-color-999">发起了问题 • 1 人关注 • 0 个回复 • 374 次浏览 • 2 小时前</span>
              <span class="text-color-999 related-topic collapse">• 来自相关话题</span>
            </p>

            <!--  -->
          </div>
        </div>
      </li>

      <li>
        <div class="aw-item" data-topic-id>
          <div class="item-img">
              <a
            class="aw-user-name hidden-xs"
            data-id="7614"
            href="https://gocn.vip/people/%E8%80%81%E9%98%B3"
            rel="nofollow"
          >
            <img src="https://gocn.vip/static/common/avatar-max-img.png" alt>
          </a>
          </div>
          <div class="aw-question-content">
            <p>
              <a href="https://gocn.vip/question/3341">25K-80K招golang方向技术研发，主管。</a>
            </p>
    
            <p>
              <a class="aw-user-name" href="https://gocn.vip/people/wluranus"  data-id="5935">wluranus</a>
              <span class="text-color-999">回复了问题 • 4 人关注 • 6 个回复 • 269 次浏览 • 18 小时前</span>
              <span class="text-color-999 related-topic collapse">• 来自相关话题</span>
            </p>

            <!--  -->
          </div>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "CommonList"
};
</script>

<style scoped>
.item-img {
    float: left

}
.aw-item{
    margin: 10px 0;
}
.pull-right{
    float: right;
}

li{
    margin-top: 10px; 
    list-style: none;
}
</style>