<template>
    <span>
        should be red/blue
    </span>
</template>

<script setup lang="ts">
const css0 = 'css0'
const css1 = 'css1'

const url = (await import(
    /* @vite-ignore */
    `~/assets/${css1}.css?url`
    )).default;

useHead({
    link: [{
        rel: 'stylesheet',
        href: url,
    }],
})
</script>