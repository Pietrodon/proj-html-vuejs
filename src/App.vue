<template>
  <div id="app">
    <HeaderComponent/>
    <MainContentHeader/>
    <CoursesComponent/>
    <SecondComponentMain/>
    
  </div>
    
  
</template>

<script>
import  HeaderComponent    from "./components/HeaderComponent.vue";
import  MainContentHeader  from "./components/MainContentHeader.vue";
import  CoursesComponent   from "./components/CoursesComponent.vue";
import  SecondComponentMain   from "./components/SecondComponentMain.vue";



export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainContentHeader,
    CoursesComponent,
    SecondComponentMain,
   
  }
}
</script>

<style lang="scss">
@import'~@fortawesome/fontawesome-free/css/all.css';


</style>
