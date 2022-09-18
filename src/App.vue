<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Hero from './components/Hero.vue'
import Navigation from './components/Navigation.vue';
import News from './components/News.vue';
import Games from './components/Games.vue';
import Careers from './components/Careers.vue';
import Footer from './components/Footer.vue';
</script>

<template lang="pug">
Navigation
Hero
News
Games
Careers
Footer
</template>

<style lang="sass">
@use '../src/style/style'
.action-button
    border: none
    background: white
    text-transform: uppercase
    font-weight: bold
    width: fit-content
    padding: 1rem 3rem
    border-radius: .5rem
    margin: 3rem 0
    &.blue
        background: #2d85f3
</style>
