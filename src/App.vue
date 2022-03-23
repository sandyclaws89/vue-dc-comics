<template>
  <div id="app">
    <HeaderDc/>
    <BannerTop/>
    <SliderMain/>
    <BlueList/>
  </div>
</template>

<script>
import HeaderDc from './components/HeaderDc.vue'
import BannerTop from './components/BannerTop.vue'
import BlueList from './components/BlueList.vue'
import SliderMain from './components/SliderMain.vue'


export default {
  name: 'App',
  components: {
        HeaderDc,
        BannerTop,
        BlueList,
        SliderMain,
    },
}
</script>

  <style lang= "scss">
    @import "./assets/styles/style.scss";
  </style>
