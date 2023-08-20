
<script setup>


</script>

<template>
    <nav>
        <div class="logo">
            <img src="src\assets\logo.png" alt="logo">
            <p class="logo-name">Findtrend</p>
        </div>

        <ul>
            <li><a href="#">Privacy Policy</a></li>
            <li><a href="#">Terms and Conditions</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Careers</a></li>
            
        </ul>

       
    </nav>
  
 
</template>

<style scoped>

.logo{
    display: flex;
    gap: 10px;
}

.logo-name{
color: #000000;
text-align: center;
font-size: 24px;
font-style: normal;
font-weight: 700;
line-height: 100%; /* 24px */
}

nav{
    display: flex;
    justify-content: space-between;
    background-color: #0000;
    align-items: center;
    padding: 40px 80px 0px 80px;

}


ul {
    display: flex;
    gap: 40px;
}

ul li {
    list-style: none;

}

a {
    text-decoration: none;
    color: #000000;
}


   

</style>