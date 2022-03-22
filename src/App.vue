<template>
  <div id="app">
    <HeaderDc/>
    <BlackHeader/>
  </div>
</template>

<script>
import BlackHeader from './components/BlackHeader.vue'

import HeaderDc from './components/HeaderDc.vue'

export default {
  name: 'App',
  components: {
        HeaderDc,
        BlackHeader
    },
}
</script>


    BlackHeader<style lang= "scss">
  @import "./assets/styles/style.scss";
</style>
