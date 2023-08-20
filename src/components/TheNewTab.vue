<script setup>
</script>


<template>
  
  <div class="newtab">
    <p class="open">Open New tabs is Sh*t</p>
    <div class="rectangle">
      <img src="src/assets/Findtrend...png" alt="img" class="findtrend">
    </div>
    <div class="solution">
      <p>A solution for your browser tabs that won't make your device slower over time. <br>Get ease and speed to discover trends with just one tab.</p>
    </div>
  </div>

</template>

<style scoped>
.newtab {
  background: #A8FF35;
  width: auto;
  height: 742px;
  flex-shrink: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.open {
  color: #000;
  font-size: 72px;
  font-weight: 700;
  line-height: normal;
}

.rectangle {
  border-radius: 16px;
  background: #F5F5F5;
  width: 502px;
  height: 202px;
  flex-shrink: 0;
  margin: 20px auto; /* Center horizontally */
  display: flex; /* Added */
  align-items: center; /* Added */
  justify-content: center; /* Added */
}


.solution {
  color: #000;
  font-size: 18px;
  font-weight: 400;
  line-height: 150%;
  margin-top: 20px; /* Add margin for space at the top */
  text-align: center;
}
</style>
