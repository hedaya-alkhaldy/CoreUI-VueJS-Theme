<template>
<Nav></Nav>
<Image></Image>
<Card></Card>
<Footer></Footer>
</template>
<script>
import {defineComponent} from 'vue'
import Nav from '@/Components/Theme/Nav'
import Image from '@/Components/Theme/Image'
import Card from '@/Components/Theme/Card'
import Footer from '@/Components/Theme/Footer'


export default defineComponent({

    components:{
    Nav,
    Footer,
    Card,
    Image

    },
})

</script>
