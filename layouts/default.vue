<template lang="">
  <div class="d-flex wrapper">
    <Sidebar class="sidebar"/>
    <div class="header-wrapper">
      <Header/>
      <nuxt/>
    </div>
  </div>
</template>
<script>
import Sidebar from '../components/Sidebar.vue';
import Header from '../components/Header.vue';
export default {
  components:{
    Sidebar,Header
  }

  
}
</script>
<style scoped >
  .wrapper{
    background-color: #dfdfdf;
    min-height: 100vh;
  }

  .header-wrapper{
    flex-grow: 1;
  }
</style>