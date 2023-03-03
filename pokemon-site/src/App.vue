<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/commons/Header.vue'
import BackgroundVue from './components/commons/Background.vue'
import Footer from './components/commons/Footer.vue'
</script>
<template>
  <header>
    <Header></Header>
    <BackgroundVue></BackgroundVue>
    
    <Footer></Footer>
  </header>
</template>
