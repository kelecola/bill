<template>
  <scroll class="wrapper"
    :data="data"
    :pulldown="pulldown"
    @pulldown="loadData">
    <ul class="content">
      <li>推荐</li>
      <li>MAD·AMV</li>
      <li>MMD·3D</li>
      <li>短片·手书·配音</li>
      <li>综合</li>
    </ul>
    <div class="loading-wrapper"></div>
  </scroll>
</template>

<script type="text/ecmascript-6">
// import BScroll from 'better-scroll'

// export default {
//   data() {
//     return {
//       data: [],
//       pulldown: true
//     }
//   },
//   created() {
//     this.loadData()
//   },
//   methods: {
//     loadData() {
//       requestData().then(res => {
//         this.data = res.data.concat(this.data)
//       })
//     }
//   }
// }
</script>
