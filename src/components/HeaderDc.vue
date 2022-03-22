<template>
<!-- NEL TEMPLATE CI METTO TUTTO IL MIO HTML.  -->
    <header>
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li v-for="(element, index) in links" :key="index">
                <a :href="element.href">{{element.text}} </a>
            </li>   
        </ul>
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
li {
    display: inline-block;
    a{
        text-decoration: none;
    }
}

</style>