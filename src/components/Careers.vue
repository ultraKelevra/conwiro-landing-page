<script setup>
import { ref } from 'vue';
import Container from './Container.vue';
    
</script>
    
<template lang="pug">
section.careers-section
    .container
        h1 Careers
    .container
        p Join us to create games that excite and help our players around the world make memories.
        button.action-button See Careers
</template>

<style lang="sass">
section.careers-section
    padding: 10rem 0
    background: rgb(50,50,50)
    >*
        color: white!important
    .container
        align-items: end
        >*
            text-align: end
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