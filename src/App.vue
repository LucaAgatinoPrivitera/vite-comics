<script setup>
import Header from './components/Header.vue'
import Body from './components/Body.vue'
import Section from './components/Section.vue'
import Footer_ from './components/Footer_.vue'
import Footer_SignUp from './components/Footer_SignUp.vue'
</script>

<template>
  <Header msg="Vite + Vue" />
  <Body></Body>
  <Section></Section>
  <Footer_></Footer_>
  <Footer_SignUp></Footer_SignUp>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
