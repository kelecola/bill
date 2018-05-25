<template>
  <div>
    <div class="head"
      ref="a">
      <ul>
        <li>
          <a>
            <span>首页</span>
          </a>
        </li>
        <li>
          <a>
            <span>动画</span>
          </a>
        </li>
        <li>
          <a>
            <span>番剧</span>
          </a>
        </li>
        <li>
          <a>
            <span>国创</span>
          </a>
        </li>
        <li>
          <a>
            <span>音乐</span>
          </a>
        </li>
        <!--<li>舞蹈</li><li>科技</li><li>游戏</li><li>娱乐</li>-->
        <!--<li>鬼畜</li><li>电影</li><li>电视剧</li>-->
        <!--<li>纪录片</li><li>影视</li><li>时尚</li>-->
        <!--<li>生活</li><li>广告</li><li>直播</li><li>相簿</li>-->
      </ul>
      <span @click="changeTo"><img src='../../../bill/static/images/11.png'></span>
    </div>
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
      <span @click="changeBack"
        class="btn"><img src="../../../bill/static/images/14.png"></span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'bnavPart',
  return: {},
  methods: {
    changeTo: function() {
      this.$refs.a.style.display = 'none'
      this.$refs.b.style.display = 'block'
      this.$refs.b.style.position = 'fixed'
      this.$refs.b.style.background = 'white'
    },
    changeBack: function() {
      // this.$refs.a.style.display = 'none'
      this.$refs.b.style.display = 'none'
      this.$refs.a.style.display = 'flex'
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
.head ul {
  display: flex;
}
.head li a {
  box-sizing: border-box;
}
.head li a:hover {
  color: rgba(251, 114, 153, 0.9);
  text-decoration: underline;
}
.head li {
  list-style-type: none;
  padding: 0.7rem 0.9rem 0 0.9rem;
  color: rgba(0, 0, 0, 0.6);
}
.head {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.head img {
  width: 2.5rem;
  height: 2rem;
}
.head span {
  padding-bottom: 1rem;
}
.head2 ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: left;
  align-content: flex-start;
}

.head2 li {
  list-style-type: none;
  padding: 0.65rem;
}
.head2 img {
  width: 2.5rem;
  height: 1.5rem;
  text-align: center;
}
.head2 {
  display: flex;
  flex-wrap: wrap;
}
.head2 .btn {
  margin: 0 auto;
}
</style>
