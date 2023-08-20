<script setup >
import { onMounted, onUnmounted } from 'vue';

const props = defineProps({
    image: {type: String, required:true}
})

onMounted(() => {

})

</script>

<template>
    <div class="connect">
        <img :src="props.image" alt="logo" class="media-logo">
    </div>

</template>

<style scoped>
.connect {
    width: 60px;
    height: 60px;
    flex-shrink: 0;
    border-radius: 80px;
    margin: 80px 140px;
    background:#FAFAFA;
    
}

.media-logo{
    display: flex;
    align-items:  center;
    padding: 32px 32px;
    background-color: white;
}

</style>