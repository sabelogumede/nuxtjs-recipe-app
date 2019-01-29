<template>
    <h1>a Single recipe, with ID: {{ $route.params.id }}</h1>
</template>

<script>
export default {
    validate (data) {
        // return data.params.id == 1
        // number validation
        return /^\d+$/.test(data.params.id)
    }
}
</script>
