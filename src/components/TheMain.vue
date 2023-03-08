<script setup>
import AppRow from '@/components/AppRow.vue'
</script>

<template>
    <ul class="flex flex-col space-y-2 md:space-y-4">
        <li v-for="num in 3" :key="num">
            <AppRow />
        </li>
    </ul>
</template>