<script setup>
import { ref } from 'vue';
import LogoConwiro from './LogoConwiro.vue';
</script>

<template lang="pug">
.navigation
    .container.navigation-container
        logo-conwiro.logo
        .navigation-anchors
            a section a
            a section b
            a section c
</template>

<style lang="sass">
.navigation
    width: 100%
    background: black
    position: sticky
    padding: 2rem 0
    top: 0
    left: 0
    color: white
    z-index: 1000
    .logo
        height: 3rem
        width: 9rem
        fill: white
    .navigation-container
        display: flex
        flex-direction: row
        justify-content: space-between
        align-items: center
    
    .navigation-anchors
        display: flex
        align-items: center
        justify-content: center
        align-content: stretch
        flex-wrap: nowrap
        gap: 2rem

</style>
    