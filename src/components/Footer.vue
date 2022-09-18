<script setup>
import { ref } from 'vue';
import Container from './Container.vue';
import LogoConwiro from './LogoConwiro.vue';
</script>
    
<template lang="pug">
.footer
    .container
        .top-section
            .social
                p Follow us on
                .social-links-container
                    a Twitter
                    a Instagram
                    a Youtube
                    a Linkedin
            .appstores
        .bottom-section
            .legal-and-details
                a Terms of Service
                a Privacy Policy
                a Parent's Guide
                a Safe and Fair Play Policy
                a Other Legal Docs
                a For Media 

            .info
                p.business-info Supercell<br>Oy Jätkäsaarenlaituri<br>1 00180 Helsinki<br>Finland

                LogoConwiro
</template>

<style lang="sass">
.footer
    background: black
    padding: 3rem 0 10rem 0
    .top-section
        .social
            margin-bottom: 2rem
            p
                font-size: 1rem
                color: gray
            .social-links-container
                display: flex
                gap: 1rem
                flex-direction: row
                a
                    color: white
                    text-decoration: none
                    font-weight: bold

    .bottom-section
        border-top: 1px solid rgb(50,50,50)
        padding: 1rem 0 0 0
        position: relative
        display: flex
        flex-direction: column
        .legal-and-details
            font-size: .8rem
            display: flex
            flex-direction: row
            gap: 2rem
            color: white
        .info
            display: flex
            flex-direction: row
            justify-content: space-between
            p
                font-size: .8rem
                line-height: 1.25rem
                color: gray
            .logo
                width: 8rem
            


</style>