<template>
    <div class="rounded-lg p-4 text-white shadow-md bg-gray-300-10 hover:bg-gray-400 hover:shadow-lg">
        <img :src="pokemon.image" :alt="pokemon.name" class="mx-auto mb-2 h-20">
        <h2 class="text-center capitalize font-bold">{{ pokemon.name }}</h2>
        <p class="text-center text-sm uppercase">{{ pokemon.type }}</p>
    </div>
</template>

<script setup>
defineProps({
    pokemon: Object
})
</script>