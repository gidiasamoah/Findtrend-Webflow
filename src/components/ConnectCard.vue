<script setup>

</script>

<template>
    <div class="icons-container">
      <div class="facebook-border">
        <img src="src/assets/fb.png" alt="Facebook" class="facebook">
      </div>
  
      <div class="twitter-border">
        <img src="src/assets/twitter.png" alt="Twitter" class="twitter">
      </div>
  
      <div class="basketball-border">
        <img src="src/assets/Elon.png" alt="Basketball" class="basketball">
      </div>

      <div class="pininterest-border">
        <img src="src/assets/pin.png" alt="pininterest" class="pininterest">
      </div>

      <div class="mail-border">
        <img src="src/assets/mail.png" alt="mail" class="mail">
      </div>

      <div class="orange-border">
        <img src="src/assets/orange.png" alt="orange" class="orange">
      </div>

      <div class="wicked-border">
        <img src="src/assets/wicked.png" alt="wicked" class="wicked">
      </div>
      
      <div class="linkedin-border">
        <img src="src/assets/linkedin.png" alt="linkedin" class="linkedin">
      </div>

    </div>
  </template>
  
  
<style>

.icons-container {
  display: flex;
  gap: 24px;
  background: #FAFAFA;
  justify-content: flex-start; /* Align items horizontally to the left */
  padding: 80px 0; /* Add padding to center vertically */
  align-items: center; /* Add margin to the container */
  margin-left: 80px;
}

/* Set a common width and height for all icons */
.facebook-border, .twitter-border, .basketball-border, .pininterest-border, .mail-border, .orange-border, .wicked-border, .linkedin-border {
  width: 124px;
  height: 124px;
  flex-shrink: 0;
  border-radius: 8px;
}

/* Add background and padding for the icons */
.facebook, .twitter, .basketball, .pininterest, .mail, .orange, .wicked, .linkedin {
  background: white;
  padding: 32px 32px;
}

/* Customize the Twitter background color */
.twitter {
  background: #A8FF35;
}




</style>

  