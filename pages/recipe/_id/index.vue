<template>
    <section>
        <Header />

        <h1>a Single recipe, with ID: {{ $route.params.id }}</h1>
        <Footer />
    </section>
    
</template>

<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'


export default {
    validate (data) {
        // return data.params.id == 1
        // number validation
        return /^\d+$/.test(data.params.id)
    },
    components: {
        Header,
        Footer
    }
}
</script>
