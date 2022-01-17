<template>
<Nav></Nav>
<Card></Card>
<Footer></Footer>
</template>
<script>
import {defineComponent} from 'vue'
import Nav from '@/Components/Theme/Nav'
import Card from '@/Components/Theme/Card'
import Footer from '@/Components/Theme/Footer'


export default defineComponent({

    components:{
    Nav,
    Footer,
    Card,

    },
})

</script>
