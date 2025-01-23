<template>
    <div>
        <h2>{{ card.title }}</h2>
        <div>
            <p>{{ card.body }}</p>
        </div>
    </div>
</template>

<script setup>
const {card} = defineProps({
    card: {type: Object, required: true}
})
</script>