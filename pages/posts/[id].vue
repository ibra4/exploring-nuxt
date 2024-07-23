<template>
    <h1>Post</h1>
    <NuxtLink to="/">Index</NuxtLink>
</template>

<script setup lang="js">
const route = useRoute()

// When accessing /posts/1, route.params.id will be 1
console.log(route.params.id)
</script>