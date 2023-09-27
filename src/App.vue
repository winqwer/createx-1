<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
  

    <div class="wrapper">
      <!-- <HelloWorld msg="You did it!" /> -->
      <img alt="logo" class="logo" src="./img/logo.svg"/>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/About us">About</RouterLink>
        <RouterLink to="/Services">Services</RouterLink>
        <RouterLink to="/Work">Work</RouterLink>
        <RouterLink to="/News">News</RouterLink>
        <RouterLink to="/Contacts">Contacts</RouterLink>
      </nav>
      <div class="phone">
    <div>
      <img src="./img/iPhone.svg" alt="">
      <div>
        <p>Call us</p>
        <a href="tel:+74055550128">+7(405)555-0128</a>
      </div>
    </div>

    <div>
      <img src="./img/Chat.svg" alt="">
      <div>
        <p>Talk to us</p>
        <a href="mailto:hello@createx.com">hello@createx.com</a>
      </div>
    </div>
  </div>
  
    </div>
  </header>

  <RouterView />
</template>

<style>


.wrapper > nav{
  display: flex;
    gap: 40px;
}

.wrapper > nav > a {
  text-decoration: none;
  color: var(--gray-800, #424551);
/* base/bold */
font-family: Ubuntu;
font-size: 16px;
font-style: normal;
font-weight: 700;
line-height: 160%; /* 25.6px */
}

header{
  height: 52px;
 
}

.phone{
  display: flex;
  gap: 36px;
}
.phone > div{
  display: flex;
  color: var(--gray-900, #1E212C);
  
  width: 190px;
  

}

.phone > div > img{
  margin: 0 12px 0 0 ;
}
.phone a{
  text-decoration: none;
  font-size: 18px;
  color: #1E212C;
}
 p{
  margin: 0;
 }

.logo {

  height: 22px;
  width: 130px;
}

.wrapper{
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}



</style>
