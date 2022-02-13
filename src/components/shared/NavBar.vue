<template>
  <div id="navbar">
    <img alt="Vue logo" src="../../assets/logo.png">
    <div id="nav">
      <router-link to="/">Home     </router-link>
      <router-link to="/about"> About</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: { }
}
</script>

<style>
  #navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1% 3% 1% 3%;
    background-color: #F4F1F0 ;
  }

  #navbar #nav {
    padding: 0;
    padding-bottom: 5px;
  }

  
</style>