<template>
<!-- NEL TEMPLATE CI METTO TUTTO IL MIO HTML.  -->
    <header class="flex">
        <div class="container flex">
                <img src="../assets/img/dc-logo.png" alt="">
            <ul class="inline">
                <li v-for="(element, index) in links" :key="index">
                <a :href="element.href">{{element.text}} </a>
                </li>   
            </ul>
        </div>
    </header>
</template>

<script>

export default {
    name: 'HeaderDc',
    data () {
        return {
            links: [
                {
                    href: '#',
                    text: 'CHARACTERS'
                },
                {
                    href: '#',
                    text: 'COMICS'
                },
                {
                    href: '#',
                    text: 'MOVIES'
                },
                {
                    href: '#',
                    text: 'TV'
                },
                {
                    href: '#',
                    text: 'GAMES'
                },
                {
                    href: '#',
                    text: 'COLLECTIBLES'
                },
                {
                    href: '#',
                    text: 'VIDEOS'
                },
                {
                    href: '#',
                    text: 'FANS'
                },
                {
                    href: '#',
                    text: 'NEWS'
                },
                 {
                    href: '#',
                    text: 'SHOP'
                },



            ]
        }
    }
}
</script>

<style scoped lang="scss">
header{
    height: 10vh;
    div{
        justify-content: space-between; 
        align-items: center;
        width: 1100px;
    }
    img{
        width: 55px;
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