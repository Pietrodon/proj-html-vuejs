<template>
  <div id="app">
    <HeaderComponent/>
    <MainContentHeader/>
    <CoursesComponent/>
    <SecondComponentMain/>
    <CarouselComponent/>
    
  </div>
    
  
</template>

<script>
import  HeaderComponent    from "./components/HeaderComponent.vue";
import  MainContentHeader  from "./components/MainContentHeader.vue";
import  CoursesComponent   from "./components/CoursesComponent.vue";
import  SecondComponentMain   from "./components/SecondComponentMain.vue";
import  CarouselComponent   from "./components/CarouselComponent.vue";



export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainContentHeader,
    CoursesComponent,
    SecondComponentMain,
    CarouselComponent,
   
  }
}
</script>

<style lang="scss">
@import'~@fortawesome/fontawesome-free/css/all.css';


</style>
