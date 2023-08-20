<script setup >
import { onMounted, onUnmounted } from 'vue';

const props = defineProps({
    image: {type: String, required:true}
})

onMounted(() => {

})

</script>

<template>
<div class="offercontainer">
    <div class="offer">
    <img :src="props.image" alt="logo" class="offer-pic">
</div>
</div>

</template>

<style scoped>

.offercontainer{
    background: black;
    width: auto;
    height: 900px;

}
.offer{
    width: auto;
    height: 82px;
    background: black;
   
}

.offer-pic{
    display: flex;
    
   
    
}

</style>