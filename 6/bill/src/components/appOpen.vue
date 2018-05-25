<template>
  <div class="bill__openbtn--openInApp">
    <img src="../../../bill/static/images/bt.png">
    <div class="bill__words--openInAppText">
      <p>App 内打开</p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'appOpen',
  return: {}
}
</script>

<style scoped>
html {
  font-size: 10px;
}
img {
  width: 100%;
  height: 100%;
  object-fit: center/cover;
}
.bill__openbtn--openInApp {
  position: fixed;
  left: 6.625rem;
  height: 4rem;
  width: 10rem;
  bottom: 1.2rem;
}
.bill__words--openInAppText {
  position: relative;
  top: -4.4rem;
  left: 24px;
  font-family: 宋体;
  font-size: 1.4rem;
  color: #fff;
  z-index: 10;
}
</style>
