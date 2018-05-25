<template>
  <div id="head"
    class="bill__head--wrapper">
    <div class="head__icon">
      <img src='../../../bill/static/images/logo.png'>
    </div>
    <div class="head__nav">
      <div class="head__searchBtn--searchLink">
        <!-- <p>search</p> -->
        <img src='../../../bill/static/images/12.png'>
      </div>
      <div class="head__loginBt--loginLink">
        <!-- <p>face</p> -->
        <img src='../../../bill/static/images/13.png'>
      </div>
      <div class="head__downloadBtn--downloadLink">
        <p class="head__downloadText--downloadText">下载 App</p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'headPart',
  return: {
    // head__icon: '../../../bill/static/images/logo.png',
    // head__searchBtn: '../../../bill/static/images/12.png',
    // head__loginBtn: '../../../bill/static/images/13.png'
  }
}
</script>
<style scoped>
* {
  margin: 0;
  padding: 0;
  border: 0;
}
html {
  font-size: 10px;
}
.bill__head--wrapper {
  height: 2.67rem;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.head__icon {
  height: 2rem;
  width: 5.17rem;
  margin-left: 0.3rem;
}
.head__nav {
  display: flex;
  justify-content: space-between;
  margin-right: 0.3rem;
  width: 11rem;
}
.head__searchBtn--searchLink {
  height: 2rem;
  width: 2rem;
}
.head__loginBt--loginLink {
  height: 2rem;
  width: 2rem;
}
.head__downloadBtn--downloadLink {
  width: 5rem;
  height: 1.6rem;
  background-color: rgba(251, 114, 153, 0.9);
  border-radius: 0.44rem;
  right: 0;
}
.head__downloadText--downloadText {
  color: #fff;
  font-family: 微软雅黑;
  font-size: 0.9rem;
  text-align: center;
  height: 1rem;
  line-height: 1.8rem;
}
img {
  width: 100%;
  height: 100%;
  object-fit: center/cover;
}
</style>
