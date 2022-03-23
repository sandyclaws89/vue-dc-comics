<template>
  <div id="app">
    <HeaderDc/>
    <BannerTop/>
    <BlueList/>
  </div>
</template>

<script>
import HeaderDc from './components/HeaderDc.vue'
import BannerTop from './components/BannerTop.vue'
import BlueList from './components/BlueList.vue'


export default {
  name: 'App',
  components: {
        HeaderDc,
        BannerTop,
        BlueList,
    },
}
</script>

  <style lang= "scss">
    @import "./assets/styles/style.scss";
  </style>
