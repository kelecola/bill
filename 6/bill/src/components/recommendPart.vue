<template>
  <div class="recommend__wrapper">
    <div class="recommend__head">
      <div class="recommend__title">
        <p>热门推荐</p>
      </div>
      <a class="recommend__rank">
        <img src="../../../bill/static/images/9.png">
      </a>
    </div>
    <div class="content1">
      <div><img src="../../../bill/static/images/1.png"></div>
      <div><img src="../../../bill/static/images/2.png"></div>
      <div><img src="../../../bill/static/images/3.png"></div>
      <div><img src="../../../bill/static/images/4.png"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'recommendPart',
  return: {}
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

img {
  width: 10rem;
  height: 10rem;
}

.recommend__wrapper {
  margin-top: 1.2rem;
}

.content1 {
  margin-top: 0.2rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

a img {
  width: 6rem;
  height: 2rem;
  padding-right: 0.5rem;
}
.recommend__head,
.mad__header {
  display: flex;
  justify-content: space-between;
}
p {
  height: 2rem;
  line-height: 2rem;
  padding-left: 0.5rem;
}
</style>
