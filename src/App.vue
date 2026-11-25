<script setup>
import Content from './Content.vue';
import Footer from './Footer.vue';
import Navbar from './Navbar.vue';
import Sidebar from './Sidebar.vue';


</script>
<template>
  <Navbar />
  <div class="center">
    <Sidebar />
    <Content />
  </div>
  <Footer/>
  
</template>

<style scoped>
.center{

display: flex;
flex-direction: row;
align-items: center;
justify-content: space-between;
}
</style>
