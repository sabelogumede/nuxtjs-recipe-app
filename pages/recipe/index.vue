<template>
<section>
    <Header />

    <div>
        <h1>This is our recipe page</h1>
    </div>
        
    <div>
        <input type="text" v-model="recipeId">
        <button @click="onLoadRecipe">Search Recipe</button>
    </div>

</section>
</template>

<script>
import Header from '~/components/Header.vue'

export default {
    components: {
        Header
    },
    data() {
        return {
            recipeId: ''
        }
    },
    methods: {
        onLoadRecipe() {
            this.$router.push('/recipe/' + this.recipeId)
        }
    }
    
}

</script>
