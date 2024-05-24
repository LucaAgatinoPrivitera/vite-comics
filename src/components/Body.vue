<script setup>
import Section from './Section.vue'
import ComicsList from './ComicsList.vue'
</script>

<template>
    <div class="bg-dark">
        <div id="jumbotron" class="w-100 m-auto container-fluid p-0">
            <img src="../assets/img/jumbotron.jpg" alt="" class="img-fluid">
        </div>
    </div>
    <ComicsList></ComicsList>
    <Section></Section>
</template>

<style scoped>
#jumbotron {
    height: 600px;
    overflow: hidden;
}
#jumbotron img{
    width: 100%;
    
}
</style>