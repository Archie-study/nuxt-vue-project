<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad veniam nemo ut magni ab minima molestias rem id eligendi ipsum?</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo, quaerat veritatis. Qui saepe exercitationem amet rem, harum voluptatibus iusto! Quia.</p>
        <div>{{ data }}</div>
    </div>
</template>

<script setup>
    const { data } = await useFetch('/api/currency/GBP')

</script>

<style scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }

    p {
        margin: 20px 0;
    }
</style>