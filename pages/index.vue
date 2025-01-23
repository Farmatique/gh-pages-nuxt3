<template>
    <h1>Hello nuxt3-gh-pages!</h1>
    <Card v-for="(card, index) in cards" :key="index" :card="card"/>
</template>

<script setup>
    import Card from '~/components/Card'

    const cards = ref([
        {title: 'Card1 title', body: 'Card 1 body'},
        {title: 'Card2 title', body: 'Card 2 body'}
    ])
</script>  