<template>
<Header></Header>
<Hero />
<Customers />
<Main></Main>
<Footer></Footer>
</template>

<script>
import Footer from "../components/Footer.vue";
import Main from "../components/Home/Main.vue";
import Header from '../components/Header.vue'
import Hero from '../components/Home/Hero.vue'
import Customers from '../components/Home/Customers.vue'

export default {
    components : {
        Header,
        Hero,
        Customers,
        Main,
        Footer
    }
}
</script>
<style lang="scss">

</style>