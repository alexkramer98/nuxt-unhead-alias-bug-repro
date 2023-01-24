<template>
    <span>
        should be red
    </span>
</template>

<script setup lang="ts">
useHead({
    link: [{
        rel: 'stylesheet',
        href: '~/assets/css/default.css',
    }],
})
</script>