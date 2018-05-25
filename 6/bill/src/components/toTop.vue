<template>
  <div class="bill__topbtn--toTop"
    href="#one">
    <img src="../../../bill/static/images/14.png"
      style="color:grey">
  </div>
</template>
<script>
export default {
  name: 'toTop',
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
.bill__topbtn--toTop {
  position: relative;
  background-color: gray;
  left: 145px;
  height: 30px;
  width: 60px;
}
</style>
