<script setup>
import TheNavBar from './components/TheNavBar.vue';
import TheHeroSection from './components/TheHeroSection.vue';
import TheNewTabVue from './components/TheNewTab.vue';
import TheLongtextVue from './components/TheLongtext.vue';
import ThePartnerSectionVue from './components/ThePartnerSection.vue';
import PartnerCards from './components/PartnerCards.vue';
import ThePlatformConnectVue from './components/ThePlatformConnect.vue';
import ConnectCard from './components/ConnectCard.vue'
import TheTwitter from './components/TheTwitter.vue'


const logos = [
  {
    id: 1,
    path: "src/assets/microsoft.png"
  },
  {
    id: 2,
    path: "src/assets/airtable.png"
  },  
  {
    id: 3,
    path: "src/assets/algolia.png"
  },
  {
    id: 4,
    path: "src/assets/allianz.png"
  },
  {
    id: 5,
    path: "src/assets/bonanza.png"
  },
  {
    id: 6,
    path: "src/assets/carrera.png"
  },
  {
    id: 7,
    path: "src/assets/coinbase.png"
  },
  {
    id: 8,
    path: "src/assets/upwork.png"
  },
  {
    id: 9,
    path: "src/assets/expedia.png"
  },
  {
    id: 10,
    path: "src/assets/verizon.png"
  },
  {
    id: 11,
    path: "src/assets/grab.png"
  },
  {
    id: 12,
    path: "src/assets/Heineken.png"
  },
  {
    id: 13,
    path: "src/assets/magento.png"
  },
 
  {
    id: 14,
    path: "src/assets/suzuki.png"
  },
  
  {
    id: 18,
    path: "src/assets/volvo.png"
  },
  {
    id: 19,
    path: "src/assets/we transfer.png"
  },
]


const medialogos = [
  {
    id: 1,
    path: "src/assets/facebook.png"
  },
  {
    id: 2,
    path: "src/assets/twitter.png"
  },  
  {
    id: 3,
    path: "src/assets/orange.png"
  },
  {
    id: 4,
    path: "src/assets/mail.png"
  },
]





</script>

<template>
  <TheNavBar/>
  <TheHeroSection/>
  <TheNewTabVue/>
  <TheLongtextVue/>
  <ThePartnerSectionVue/>
  <div class="cards">
    <PartnerCards v-for="logo in logos" :image="logo.path" :key="logo.id"/>
  </div>
  <ThePlatformConnectVue/>
  <div class="connect">
    <ConnectCard v-for="medialogo in medialogos" :image="medialogo.path" :key="medialogo.id"/>
  </div>
  
  <TheTwitter/>
  
</template>

<style scoped>

  @import  url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;700;800&display=swap');


.cards{
    display: flex;
    flex-wrap: wrap;
}

.connect{
  display: flex;
  
}
</style>