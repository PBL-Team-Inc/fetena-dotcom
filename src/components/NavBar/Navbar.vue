<template>
  <nav>
    <router-link id="logo" to="/Home"><logo/></router-link>
    <div class="">
      <router-link class="sign" to="/signup">Sign Up</router-link> 
    <router-link class="sign" to="/signin">Sign In</router-link>
    </div>
  </nav>
  <router-view/>
</template>

<script>
import logo from '../logo.vue'
export default {
components:{
    logo
  }
}
</script>

<style>
nav {
  display: flex;
  justify-content: space-between;
  padding: 4vh;
  align-items: center;
}

nav .sign {
   text-decoration: none;
   color: #fff;
   margin-left: 4vh;
   border: 1px solid #F6921E;
   padding: 0.5rem 2rem;
   border-radius: 16px;
   height: 4vh;
   width:8vh;
   
}

nav a.router-link-exact-active {
  color: #F6921E;
}
</style>