<script setup>
</script>
    
<template lang="pug">
div.container
    slot
</template>
    
<style lang="sass">
.container
    margin-inline: auto
    width: 60rem
    position: relative
    height: 100%
    display: flex
    flex-direction: column
    justify-content: center
    
//ipad-whide
@media(max-width: 1024px)
    .container
        width: 40rem
//ipad-short
@media(max-width: 820px)

//ipad-small
@media(max-width: 768px)
    .container
        width: unset
        margin-inline: 2rem
    
//phone
@media(max-width: 480px)
</style>
    