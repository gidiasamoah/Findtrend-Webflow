<script setup>
import ButtonComponent from './ButtonComponent.vue';

</script>

<template>

   <div class="hero">
    <div class="conatiner">
        <p class="main-text">Minimize your tabs
            <br> Find the trends!.</p>
        
   </div>

   <div class="sub-text">
        <p>Don’t let your computer memories consumes all of those browser tabs. 
        <br>Findtrend  let you gathers all of your favorite website into one place.</p>
   </div>

   <div class="start-button">
         <ButtonComponent class="custom-button" buttonText="Get Started" />
    </div>

    <div class="rec-one">
        <img src="src\assets\twitter.png" alt="twitter">
        <P class="tweet">Cryptopunk - Search</P>
    </div>

    <div class="rec-two">
        <img src="src\assets\pin.png" alt="twitter">
        <P class="Pin">Popular Design - Search</P>
    </div>
    
    <div class="rec-three">
        <img src="src\assets\fb.png" alt="twitter">
        <P class="fb">Product Design - Search</P>
    </div>

    <div class="rec-four">
        <img src="src\assets\Elon.png" alt="twitter">
        <P class="tweet">Cryptopunk - Search</P>
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

.rec-one{
    display: flex;
    gap: 10px;
    width: 341.226px;
    height: 82px;
    transform: rotate(-4deg);
    flex-shrink: 0;
    background: #181818;
    align-items: center;
    margin-left: 106px ;
    margin-bottom: 163.4;
    padding-left: 20px;
    z-index: 4;
}

.tweet{
    color: #FFF;
    text-align: center;
    font-size: 23.806px;
    font-style: normal;
    font-weight: 400;
    line-height: normal; 
    
    
}


.rec-two{
    display: flex;
    width: 341.226px;
    height: 82px;
    transform: rotate(2deg);
    flex-shrink: 0;
    background: #181818;
    align-items: center;
    margin-left: 308px ;
    padding-left: 20px;
    z-index: 3;
    gap: 10px;
}

.Pin{
    color: #FFF;
    text-align: center;
    font-size: 23.806px;
    font-style: normal;
    font-weight: 400;
    line-height: normal; 
    
}

.rec-three{
    display: flex;
    width: 341.226px;
    height: 82px;
    transform: rotate(-2deg);
    flex-shrink: 0;
    background: #181818;
    align-items: center;
    margin-left: 559px ;
    padding-left: 20px;
    z-index: 2;
    gap: 10px;
}

.fb{
    color: #FFF;
    text-align: center;
    font-size: 23.806px;
    font-style: normal;
    font-weight: 400;
    line-height: normal; 
    
}


.rec-four{
    display: flex;
    width: 341.226px;
    height: 82px;
    transform: rotate(4deg);
    flex-shrink: 0;
    background: #181818;
    align-items: center;
    margin-left: 827px ;
    padding-left: 20px;
    z-index: 1;
    gap: 10px;
}

.Elon{
    color: #FFF;
    text-align: center;
    font-size: 23.806px;
    font-style: normal;
    font-weight: 400;
    line-height: normal; 
    
}



</style>