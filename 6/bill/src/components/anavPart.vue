<template>
  <div ref="b"
    class="head2"
    style="display:none">
    <ul>
      <li>首页</li>
      <li>动画</li>
      <li>番剧</li>
      <li>国创</li>
      <li>音乐</li>
      <li>舞蹈</li>
      <li>科技</li>
      <li>游戏</li>
      <li>娱乐</li>
      <li>鬼畜</li>
      <li>电影</li>
      <li>电视剧</li>
      <li>纪录片</li>
      <li>影视</li>
      <li>时尚</li>
      <li>生活</li>
      <li>广告</li>
      <li>直播</li>
      <li>相簿</li>
    </ul>
    <div class="btn"><img src="../../../bill/static/images/14.png"></div>
  </div>
</template>
<script>
export default {
  name: 'anavPart',
  return: {},
  methods: {
    change: function() {
      // this.$refs.a.style.display = 'none'
      this.$refs.b.style.display = 'none'
      this.$refs.a.style.display = 'block'
    }
  }
}
</script>
<style scoped>
* {
  margin: 0;
  padding: 0;
}

html {
  font-size: 45px;
}
ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: left;
  align-content: flex-start;
}

li {
  list-style-type: none;
  padding: 0.65rem;
}
img {
  width: 2.5rem;
  height: 1.5rem;
  text-align: center;
}
.head2 {
  display: flex;
  flex-wrap: wrap;
}
.btn {
  margin: 0 auto;
}
</style>
