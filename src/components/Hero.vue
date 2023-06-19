<template>
        <div class="hero__wrapper--heading">
            <h1 class="heading__text">Protoapp</h1>
            <div>
                <p class="details__text">Our landing page template works on all devices, so you only have to set it up once, and get beautiful results forever.</p>
            </div>
            <button>Get Started</button>
        </div>
        <div class="hero__wrapper--leaves">
            <img :src="BGLeaves" alt="Leaves">
        </div>

        <div class="hero__wrapper--decal">
            <img :src="BGDecal" alt="Decal">
        </div>
        
        <div class="hero__wrapper--badgebutton">
            <BadgeButton />
        </div>
    
</template>
<script setup>
import BadgeButton from './BadgeButton.vue';
import BGLeaves from '../assets/bg-leaves.svg'
import BGDecal from '../assets/bg-decals.svg'
</script>
