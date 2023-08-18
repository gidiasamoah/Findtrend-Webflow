<script setup>
import ButtonComponent from './ButtonComponent.vue';

</script>

<template>
    <nav>
        <div class="logo">
            <img src="c:\Users\GIDEON ASAMOAH\Downloads\Vector.png" alt="logo">
            <p class="logo-name">Findtrend</p>
        </div>

        <ul>
            <li><a href="#">About</a></li>
            <li><a href="#">How it works</a></li>
            <li><a href="#">Pricing</a></li>
            <li><a href="#">Solution</a></li>
            <li><a href="#">Features</a></li>
        </ul>

        <div class="nav-buttons">
            <a href="#">Login</a>
            <ButtonComponent buttonText="Register" />
        </div>

    </nav>
  
 
</template>

<style scoped>

.logo{
    display: flex;
    gap: 10px;
}

.logo-name{
color: #FFF;
text-align: center;
font-size: 24px;
font-style: normal;
font-weight: 700;
line-height: 100%; /* 24px */
}

nav{
    display: flex;
    justify-content: space-between;
    background-color: black;
    align-items: center;

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
    color: white;
}

.nav-buttons {
    display: flex;
    align-items: center;
    gap: 40px;
}
   

</style>