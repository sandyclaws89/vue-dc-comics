<template>
  <header class="flex">
        <div class="container flex"> 
            <ul class="inline">
                <li v-for="(element, index) in categories" :key="index">
                <a :href="element.href">{{element.text}} 
                    <!-- <img src{{element.img}} alt=""> -->
                </a>
                </li>   
            </ul>
        </div>
    </header>
</template>

<script>
export default {
    name: 'BlueHeader',
    data () {
        return {
            categories :[
            {
                img: "../assets/img/buy-comics-digital-comics.png",
                text: 'DIGITAL COMICS',
                link: '#',
            },
             {
                img: "../assets/img/buy/buy-comics-digital-comics.png",
                text: 'DIGITAL COMICS',
                link: '#',
            },
             {
                img: "../assets/img/buy/buy-comics-digital-comics.png",
                text: 'DIGITAL COMICS',
                link: '#',
            },
             {
                img: "../assets/img/buy/buy-comics-digital-comics.png",
                text: 'DIGITAL COMICS',
                link: '#',
            },
             {
                img: "../assets/img/buy/buy-comics-digital-comics.png",
                text: 'DIGITAL COMICS',
                link: '#',
            },
            ]
        }
    }
}
</script>

<style  scoped lang="scss">
header{
    height: 10vh;
    div{
        justify-content: space-between; 
        align-items: center;
        width: 1100px;
    }
    li {
        display: inline-block;
        a{
            text-decoration: none;
            padding: 0 15px;
            font-size: .8rem;
            color: black;
            font-weight: 550;
        }
    }
}
</style>