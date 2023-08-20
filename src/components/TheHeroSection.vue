<script setup>
import ButtonComponent from './ButtonComponent.vue';

</script>

<template>

   <div class="hero">
    <div class="container">
        <p class="main-text">Minimize your tabs
            <br> Find the trends!</p>
        
   </div>

   <div class="sub-text">
        <p>Don’t let your computer memories consumes all of those browser tabs. 
        <br>Findtrend  let you gathers all of your favorite website into one place.</p>
   </div>

   <div class="start-button">
         <ButtonComponent class="custom-button" buttonText="Get Started" />
    </div>

   </div>


</template>


<style scoped>
.hero{
    background: black;
    position: relative;
}

.main-text {
color: #FFF;
text-align: center;
font-size: 72px;
font-style: normal;
font-weight: 900;
line-height: 112%; /* 80.64px */
background: black;
padding-top: 198px;
}

.sub-text {
    color: #8B8B8B;
text-align: center;
font-size: 18px;
font-style: normal;
font-weight: 400;
line-height: 150%; /* 27px */
padding-top: 24px;
}


.start-button {
    display: inline-flex;
    padding: 16px 32px;
    justify-content: center;
    align-items: center;
    gap: 10px;
    margin: 40px 550px;
}

.custom-button {
    background: #A8FF35
   

}





</style>