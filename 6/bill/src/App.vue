<template>
  <div>
    <head-part id="one"></head-part>
    <bnav-part></bnav-part>
    <slide-part style="overflow:hidden"></slide-part>
    <recommend-part></recommend-part>
    <mad-part></mad-part>
    <anav-part style="display:none"></anav-part>
    <app-open></app-open>
    <a href="#one">
      <to-top></to-top>
    </a>
    <foot-part></foot-part>
    <router-view/>
  </div>
</template>

<script>
import headPart from './components/headPart'
import bnavPart from './components/bnavPart'
import slidePart from './components/slidePart'
import recommendPart from './components/recommendPart'
import madPart from './components/madPart'
import anavPart from './components/anavPart'
import appOpen from './components/appOpen'
import toTop from './components/toTop'
import footPart from './components/footPart'
export default {
  name: 'App',
  data() {
    return {}
  },
  components: {
    headPart,
    bnavPart,
    slidePart,
    recommendPart,
    madPart,
    anavPart,
    appOpen,
    toTop,
    footPart
  }
}
</script>

<style>

</style>
