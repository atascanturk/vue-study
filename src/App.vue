

<template>
<div>
   <Navbar/>
    <Sidebar/>
<div class="container" >

</div> 

</div>
 
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
 import './assets/sidebars.js';
 import Navbar from './components/Navbar.vue'
 import Sidebar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    Navbar,
    Sidebar
  }
}
 
</script>


<style>
@import './assets/sidebars.css';
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
} */


</style>
