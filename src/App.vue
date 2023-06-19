<template>
    <div class="wrapper">
        <Navbar />
        <Hero />
    </div>
    <UpperMain />
    <LowerMain />
    <Footer />
</template>

<script setup>
import './sass/main.scss'
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue'
import UpperMain from './components/UpperMain.vue'
import LowerMain from './components/LowerMain.vue';
import Footer from './components/Footer.vue';
</script>