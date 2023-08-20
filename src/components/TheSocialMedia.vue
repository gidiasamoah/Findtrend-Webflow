<script setup >
import { onMounted, onUnmounted } from 'vue';

const props = defineProps({
    image: {type: String, required:true}
})

onMounted(() => {

})

</script>

<template>
<div class="socialcontainer">
    <div class="social">
    <img :src="props.image" alt="logo" class="social-logo">
</div>
</div>

</template>

<style scoped>

.socialcontainer{
    background: black;
    width: auto;
}
.social{
    width: autopx;
    height: 82px;
    flex-shrink: 0;
    margin: 80px auto;
}

.social-logo{
    display: flex;
    padding: 28px 41px;
    
}

</style>