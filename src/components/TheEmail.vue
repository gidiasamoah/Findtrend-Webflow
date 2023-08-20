<script scoped>
import ButtonComponent from './ButtonComponent.vue';

</script>

<template>

    <div class="email-container">

        <p class="join">Join us on email for </p>
        <P class="trending">more trending topics</P>

        <div class="start-button">
            <ButtonComponent class="custom-button" buttonText="Get Started" />
        </div>
        
        

    </div>

    



</template>

<style scoped>
.email-container{
    width: auto;
    height: 539px;
    flex-shrink: 0;
    background: #A8FF35;
    position: relative;
}

.join {
    color: #000;
    text-align: center;
    padding-top: 140px;
    font-size: 72px;
    font-style: normal;
    font-weight: 900;
    line-height: 112%; /* 80.64px */
}

.trending{
    color: #87D322;
    text-align: center;
    font-size: 72px;
    font-style: normal;
    font-weight: 900;
    line-height: 112%; /* 80.64px */
}

.joinnow-button{

    z-index: 999;
}
</style>