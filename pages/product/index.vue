<template>
    <ul v-for="product in products.products">
        <li>
            {{ products.title }}
        </li>
    </ul>
</template>

<script setup>
    const {data: products} = await useFetch('https://dummyjson.com/products')
</script>