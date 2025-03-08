<template>
    <h1 class="text=3xl font-bold underline">
        this.product is {{ id }} product
    </h1>
</template>

<script setup>
    const { id } = useRoute().params
</script>