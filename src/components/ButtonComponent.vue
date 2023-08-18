<script setup>
defineProps(["buttonText"]);

</script>

<template>
  <button>{{ buttonText }}</button>
 
</template>

<style scoped>
button {
    padding: 12px 32px;
    border-radius: 40px;
    background: #fff;

}

</style>