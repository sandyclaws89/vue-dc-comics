<template>
  <div class="comic">
      <img :src="comicImg" alt="">
      <h2>{{ comicType }}</h2>
  </div>
</template>

<script>
export default {
    name: 'CardComic',
    props :{
        comicImg: String,
        comicType: String
    }
}
</script>

<style>

</style>