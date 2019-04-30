
<template>
  <nav class="navigation">
    <div class="navigation__menu">
      <span class="link__wrapper">
        <router-link class="link" to="/">Home</router-link>
      </span>
      <span class="link__wrapper"> 
        <router-link class="link" to="/houses">Houses</router-link>
      </span>
      <span class="link__wrapper"> 
        <router-link class="link" to="/offices">Offices</router-link>
      </span>
      <span class="link__wrapper"> 
        <router-link class="link" to="/Services">Services</router-link>
      </span>
      <span class="link__wrapper">
        <router-link class="link" to="/Contact">Contact</router-link>
      </span>
      <span class="link__wrapper">
        
      <router-link class="link" to="/About">About</router-link>
      </span>
    </div>
    <div>
      <button class="navbar__button">
        Post a property
      </button>
    </div>
  </nav>
</template>
 <script>
 export default {
   name: 'Navigation',
 }
 </script>
 
 <style scoped>
 .navigation {
   background: #354A5F;
   padding: 1.8em;
   display: flex;
   justify-content: space-between;
 }
 .navigation__menu {
   display: flex;
   align-content: center;
   justify-content: center;
   flex: 1;
 }
 .link {
   color: #fcfcfc;
   padding: 0.5 3em;
   text-decoration: none;
 }
 .link__wrapper {
   padding: 0.5em 1em;
 }
 .navbar__button {
   background: #66DBB7;
   border: none;
   padding: 0.65em 1em;
   border-radius: 5px;
   color: #ffffff;
 }
 </style>
 