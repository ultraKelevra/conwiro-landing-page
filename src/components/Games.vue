<script setup>
import { ref } from 'vue';
import Container from './Container.vue';

</script>
    
<template lang="pug">
section.games-section
    .container
        h1 Games
    .container
        p Our dream is to create games that as many people as possible play for years and that are remembered forever.
        button.action-button See Games
</template>

<style lang="sass">
section.games-section
    padding: 10rem 0
    background: #2d85f3
    >*
        color: white!important
    .container
        align-items: start
        >*
            text-align: start
        .news
            position: relative
            p,
            span,
            h1,h2,h3,h4,h5
                width: fit-content
        h1
            margin-bottom: 3rem
        img
            width: 100%

</style>