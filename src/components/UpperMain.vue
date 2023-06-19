<template>
    <div class="uppermain__wrapper">
        <div class="uppermain__heading">
            <h2 class="heading__text">Meet Protoapp</h2>
            <p class="details__text">The app lorem ipsum is common placeholder text used to demonstrate the graphic elements of a docoument or visual presentation</p>
        </div>
        
            <FeatureItem 
            title="Discover" 
            details="Get information on using these guidelines whenever you are using therefore they have the same style and quality" 
            :img="ProductSearch" 
            class="flex__feature"/>

            <FeatureItem 
            title="Augmented" 
            details="Word salad often arouses curiosity due to its seemingly intelligent and tasteful play on words" 
            :img="ProductSmartphone" 
            class="flex__feature--reverse"/>

            <FeatureItem 
            title="Endless Possibilities" 
            details="Management Systems shouldn't be a bore. Run out of words? heres some lorem ipsum: Lorem ipsum dolor sit amet." 
            :img="ProductWork" 
            class="flex__feature"/>
        
    </div>
</template>
<script setup>
import FeatureItem from './FeatureItem.vue';
import ProductSearch from '../assets/product-search.svg'
import ProductSmartphone from '../assets/product-smartphone.svg'
import ProductWork from '../assets/product-work.svg'
</script>