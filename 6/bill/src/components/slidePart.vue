<template>
  <div class="slide__wrapper"
    ref="wrapper">
    <ul class="slide__content">
      <li>推荐</li>
      <li>MAD·AMV</li>
      <li>MMD·3D</li>
      <li>短片·手书·配音</li>
      <li>综合</li>
    </ul>
  </div>
</template>
<script type="text/ecmascript-6">
// import BScroll from 'better-scroll'
// let wrapper = document.querySelector('.slide__wrapper')
// let scroll = new BScroll(wrapper, {})
export default {
  name: 'slidePart'
  // mounted() {
  //   this.$nextTick(() => {
  //     this.scroll = new Bscroll(this.$refs.wrapper, {})
  //   })
  // }
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
  overflow: hidden;
  white-space: nowrap;
  height: 8rem;
  width: 30rem;
}

li:hover {
  color: rgba(251, 114, 153, 0.9);
}
li {
  float: left;
  list-style-type: none;
  color: rgba(0, 0, 0, 0.6);
  margin: 1rem;
}
.slide__wrapper {
  height: 2.8rem;
}
</style>
