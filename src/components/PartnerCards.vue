<script setup >
import { onUnmounted } from 'vue';

const props = defineProps({
    image: {type: String, required:true}
})

onMounted()

</script>

<template>
<div class="card">
    <img src="src/assets/microsoft.png" alt="logo" class="card-logo">
</div>

</template>

<style scoped>
.card{
    width: 266px;
    height: 120px;
    flex-shrink: 0;
    border-radius: 8px;
    background: #F5F5F5;
    margin: 80px 140px;
}

.card-logo{
    display: flex;
    align-items:  center;
    padding: 38px 40px;
}

</style>