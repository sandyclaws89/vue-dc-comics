<template>
  <div>
      <div class="comic-card">
          <img :src="comicImg" alt="">
           <span>{{ comicType }}</span>
      </div>
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
    .comic-card{
        width: calc(1100px /6);
        padding-top: 20px;
        /* height: 99px; */
    }
    img{
        
        padding: 5px;
        object-fit: fill;
        height: 150px;
        width: 100%;

    }
    span{
        display:block;
        color: white;
    }
</style>