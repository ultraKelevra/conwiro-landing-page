<script setup>
import { ref } from 'vue';
import Container from './Container.vue';
const newsList = ref([
    {
        title: "title_1",
        tags: ["news", "cool"],
        img: "/news-thumbnail.jpg",
        link: "/news-thumbnail.jpg",
    },
    {
        title: "title_2",
        tags: ["news", "cool"],
        img: "/news-thumbnail.jpg",
        link: "/news-thumbnail.jpg",
    },
    {
        title: "title_3",
        tags: ["news", "cool"],
        img: "/news-thumbnail.jpg",
        link: "/news-thumbnail.jpg",
    },
]);
</script>
    
<template lang="pug">
section.news-section
    .container
        h1 News
    .container
        a.news(v-for="news in newsList" key="title" :href="news.link")
            img(src="/news-thumbnail.jpg")
            p {{news.title}}
            .tags
                .tag(v-for="tag in news.tags" :key="tag")
</template>

<style lang="sass">
section.news-section
    padding: 10rem 0
    min-height: 100vh
    .container
        display: grid
        gap: 1rem
        grid-template-columns: repeat(2, 1fr)
        .news
            text-decoration: none
            color: rgb(50,50,50)
            position: relative
            p,
            span,
            h1,h2,h3,h4,h5
                text-align: center
                width: 100%
        h1
            margin-bottom: 3rem
        img
            width: 100%

</style>
    