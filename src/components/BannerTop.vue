<template>
        <div class="flex relative">
           <img src="../assets/img/jumbotron.jpg" alt="" >
           <span>
               CURRENT SERIES
           </span>
        </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
        div{
            width: 100%;
            justify-content: center;
            align-items: center; 
            img{
                height: 40vh;            
                width: 100vw;
                object-fit: fill;
            }
            span {
                position: absolute;
                bottom: -8px;
                left: 19rem;
                color: white;
                font-weight: 600;
                line-height: 2rem;
                background-color: blue;
                padding:0 1rem;
                z-index: 555;
            }
        }
</style>