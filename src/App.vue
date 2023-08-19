<script setup>
import TheNavBar from './components/TheNavBar.vue';
import TheHeroSection from './components/TheHeroSection.vue';
import TheNewTabVue from './components/TheNewTab.vue';
import TheLongtextVue from './components/TheLongtext.vue';
import ThePartnerSectionVue from './components/ThePartnerSection.vue';
import PartnerCards from './components/PartnerCards.vue';


</script>

<template>
  <TheNavBar/>
  <TheHeroSection/>
  <TheNewTabVue/>
  <TheLongtextVue/>
  <ThePartnerSectionVue/>
  <div class="cards">
    <PartnerCard :image="src/assets/microsoft.png" />
  </div>
  
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;700;800&display=swap');

</style>
