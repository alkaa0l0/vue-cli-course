<template>

  <div class="wrapper">

    <Header />

    <div class="wrapper-content">
      <div class="container">
        <router-view></router-view>
      </div>
   </div>

  <Footer />
 
  </div>
</template>

<script>


import TheHeader from '@/components/TheHeader'
import TheFooter from '@/components/TheFooter'
// import { RouterView } from 'vue-router';

export default {
  components: {Header: TheHeader, Footer: TheFooter},
};


</script>

<style lang="scss">


</style>







