<template>
    <p v-show="status">Component Testing: {{ status }}</p>
</template>

<script>
    export default {
        name: 'Sidebar',
        props: {
            status: Boolean
        }
    }
</script>

<style scoped>

</style>
