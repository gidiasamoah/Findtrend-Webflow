<script scoped>
    
import ButtonComponent from './ButtonComponent.vue';
</script>

<template>
    <div class="tweets">
        <img src="src/assets/tweet 1.png" alt="tweet" class="tweet1">
        <img src="src/assets/tweet 2.png" alt="tweet" class="tweet2">
        <img src="src/assets/tweet 3.png" alt="tweet" class="tweet3">
    </div>

    <div class="start-button">
         <ButtonComponent class="custom-button" buttonText="Get Started" />
    </div>

         
   

</template>

<style scoped>

.tweets{
        
        background: #FAFAFA;
    }
.tweet1{
        margin: 77px 320px;
        
        
    }
.tweet2{
        padding: 43px 320px;
     
        
    }
.tweet3{
        padding: 40px 320px;
        
        
    }





</style>