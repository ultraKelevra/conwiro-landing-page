<script setup>
import { ref } from 'vue';
import Container from './Container.vue';
</script>

<template lang="pug">
section.hero-section
  container
    img(src="../assets/conwiro-logo.svg")
    p Makers of Hay Day, Clash of Clans, Boom Beach, Clash Royale and Brawl Stars. 

</template>

<style lang="sass">
section.hero-section
  width: 100vw
  height: 100vh
  background: url("../assets/hero_bg.jpg")
  background-size: contain
  background-color: white
  background-position: center
  background-repeat: no-repeat
  .container
    height: 100%
    align-content: center
    img
      height: 7rem
      margin-inline: auto
    p
      margin-inline: auto
      text-align: center
</style>
