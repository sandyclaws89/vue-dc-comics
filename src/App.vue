<template>
  <div id="app">
    <HeaderDc/>
    <BlackHeader/>
    <BlueHeader/>
  </div>
</template>

<script>
import HeaderDc from './components/HeaderDc.vue'
import BlackHeader from './components/BlackHeader.vue'
import BlueHeader from './components/BlueHeader.vue'


export default {
  name: 'App',
  components: {
        HeaderDc,
        BlackHeader,
        BlueHeader,
    },
}
</script>


    BlackHeader<style lang= "scss">
  @import "./assets/styles/style.scss";
</style>
