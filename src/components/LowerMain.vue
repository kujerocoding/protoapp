<template>
    <div class="lowermain__wrapper">

        <div class="lowermain__top">
            <div class="top__wrapper--heading">
                <h2>Deep dive. Ready?</h2>
                <p>So are we. Unless. You're. Not. Word filler.</p>
            </div>
            <BadgeButton />
            <div class="top__wrapper--decal">
                <img :src="Decal2" alt="Decal 2">
            </div>
        </div>

        <div class="lowermain__bottom">
            <div class="bottom__wrapper--heading">
                <h2>Last Call to Action</h2>
                <p>Another section content goes here</p>
            </div>
            <div class="flex__lowermain--card">
                <Card 
                class="card__wrapper flex__card card__bg--orange"
                context="automation"
                title="automatic prototyping"
                subtitle="roll out"
                :img="Laravel"
                description="Webpack is the most powerful and flexible asset compilation tool available today. With that power, however, comes a certain level of complexity." />

                <Card 
                class="card__wrapper flex__card card__bg--bluegreen"
                context="simplicity"
                title="complexity simplified"
                subtitle="sip coffee"
                :img="Glasses"
                description="I know too many backend developers who are stifled by one glaring phobia: CSS. How do you construct a layout when nothing lines up?" />
            </div>
        </div>
        <div>
            <img :src="Decal3" alt="Decal 3">
        </div>

    </div>
</template>
<script setup>
import BadgeButton from './BadgeButton.vue';
import Decal2 from '../assets/bg-decals2.svg'
import Card from './Card.vue';
import Laravel from '../assets/badge.laravel-mix.svg'
import Glasses from '../assets/badge.how-to-read-code.svg'
import Decal3 from '../assets/bg-decals3.svg'
</script>
