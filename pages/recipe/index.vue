<template>
    <!-- <div>
        <h1>this is our recipe page</h1>
    </div> -->
        
    <div>
        <input type="text" v-model="recipeId">
        <button @click="onLoadRecipe">Search Recipe</button>
    </div>
</template>

<script>
export default {
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
