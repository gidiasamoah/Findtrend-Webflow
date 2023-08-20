<template>
    <div>
      <p class="deal">Get your best deal</p>
    </div>
  
    <div class="toggle-container">
      <div class="centered-elements">
        <p class="monthly">Monthly</p>
        <img src="src/assets/toggle.png" alt="toggle" class="toggle button">
        <p class="yearly">Yearly</p>
        <img src="src/assets/save.png" alt="save">
      </div>
    </div>
  </template>
  
  <style scoped>
  .deal {
    color: #FFF;
    text-align: center;
    font-size: 64px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    margin-top: 140px;
    background: #000;
  }
  
  .toggle-container {
    display: flex;
    background-color: black;
    justify-content: center; /* Center the elements horizontally */
    padding: 40px 0; /* Adjust top and bottom padding */
    color: #FFF;
    font-family: Inter;
    font-size: 24px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
  }
  
  .centered-elements {
    display: flex;
    align-items: center; /* Center the elements vertically */
  }
  .yearly {
    color: #F5F5F5;
  }
  /* Add margin to the items to space them 24px apart */
  .centered-elements > * {
    margin: 0 15px; /* Half of 24px to space them 24px apart */
  }
  </style>
  
  
  