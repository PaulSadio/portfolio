<script setup>
import Navigation from '@/views/Navigation.vue'
import Education from '@/views/Education.vue'
import Porfolio from '@/views/Portfolio.vue'
import Skills from '@/views/Skills.vue'
import MyFooter from './views/MyFooter.vue'

</script>

<template>
  <div class="d-flex flex-column">
    <Navigation />
    <RouterView />
    <Education />
    <Porfolio />
    <div class="d-flex flex-column ft">
      <Skills />
      <MyFooter/>
    </div>
  </div>

</template>

<style scoped>
.ft{
  height: 100vh;
}
</style>
