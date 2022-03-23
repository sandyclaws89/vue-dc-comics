<template>
  <div class="flex main-container">
        <div class="container flex"> 
            <ul class="inline">
                <li v-for="(element, index) in categories" :key="index">
                <a :href="element.href">
                    <img :src="element.img" alt="">
                    <!-- /*FIXME:SISTEMA IMG*/ -->
                    <span>{{element.text}}</span>
                </a>
                </li>   
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BlueList',
    data () {
        return {
           categories :[ 
            {
                img: "../assets/img/buy-comics-digital-comics.png",
                text: 'DIGITAL COMICS',
                link: '#',
            },
            {
                img: "../assets/img/buy-comics-digital-comics.png",
                text: 'DC MERCHANDISE',
                link: '#',
            },
             {
                img: "../assets/img/buy-comics-digital-comics.png",
                text: 'SUBSCRIPTION',
                link: '#',
            },
             {
                img: "../assets/img/buy-comics-digital-comics.png",
                text: 'COMIC SHOP LOCATOR',
                link: '#',
            },
             {
                img: "../assets/img/buy-comics-digital-comics.png",
                text: 'DC POWER VISA',
                link: '#',
            },
            ]
        }
    }
}
</script>

<style  scoped lang="scss">
.main-container{
    height: 10vh;
    background-color: blue;
    justify-content: space-around
    div{
        justify-content: space-between; 
        align-items: center;
        width: 1100px;
    }
    li {
        display: inline-block;
        a{
            text-decoration: none;
        }
        img{
            height: 35%;
        }
        span{
             color: black;
            font-weight: 550;
            display: inline;
        }
    }
}
</style>