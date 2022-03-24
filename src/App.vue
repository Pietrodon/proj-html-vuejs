<template>
  <div id="app">
    <HeaderComponent/>
    <MainContentHeader/>
    <CoursesComponent/>
    
  </div>
    
  
</template>

<script>
import  HeaderComponent    from "./components/HeaderComponent.vue";
import  MainContentHeader  from "./components/MainContentHeader.vue"
import  CoursesComponent   from "./components/CoursesComponent.vue"


export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainContentHeader,
    CoursesComponent,
   
  }
}
</script>

<style lang="scss">
@import'~@fortawesome/fontawesome-free/css/all.css';


</style>
