<template>
    <div class="feature__wrapper">
        <div class="feature__wrapper--text">
            <h3 class="heading__text">{{ title }}</h3>
            <p class="details__text">{{ details }}</p>
        </div>
        <div class="feature__wrapper--img">
            <img :src="img" alt="">
        </div>
    </div>
</template>
<script setup>
defineProps(['title', 'details', 'img'])
</script>
