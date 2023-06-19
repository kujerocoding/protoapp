<template >
    <div :class="class">
        <div class="card__wrapper--img">
            <div>
                <img :src="img" alt="">
            </div>
            <p>{{ context }}</p>
        </div>
        <div class="card__wrapper--text">
            <h4>{{ subtitle }}</h4>
            <h3>{{ title }}</h3>
            <p>{{ description }}</p>
        </div>
    </div>
</template>
<script setup>
defineProps(['class', 'context', 'title','subtitle', 'img', 'description'])
</script>
