<template>
  <div id="app">
    <HeaderComponent/>
    <MainContentHeader/>
  </div>
    
  
</template>

<script>
import  HeaderComponent from "./components/HeaderComponent.vue";
import  MainContentHeader from "./components/MainContentHeader.vue"


export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainContentHeader,
   
  }
}
</script>

<style lang="scss">
@import'~@fortawesome/fontawesome-free/css/all.css';

</style>
