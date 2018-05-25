<template>
  <div class="mad_wrapper">
    <div class="mad__header">
      <div>
        <p>MAD.AMV</p>
      </div>
      <a>
        <img src="../../../bill/static/images/10.png">
      </a>
    </div>
    <div class="content1">
      <div><img src="../../../bill/static/images/5.png"></div>
      <div><img src="../../../bill/static/images/6.png"></div>
      <div><img src="../../../bill/static/images/7.png"></div>
      <div><img src="../../../bill/static/images/8.png"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'madPart',
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
.mad_wrapper {
  margin-top: 1.2rem;
}
img {
  width: 10rem;
  height: 10rem;
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
