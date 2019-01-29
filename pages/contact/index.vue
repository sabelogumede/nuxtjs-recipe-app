<template>
    <section>
        <Header />
        
        <h1>This is our contact page</h1>

        <Footer />
    </section>
</template>


<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'

export default {
    components: {
        Header,
        Footer
    }
    
}
</script>
