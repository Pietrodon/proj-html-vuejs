<template>
  <div id="app">
    <HeaderComponent/>
    <MainContentHeader/>
    <CoursesComponent/>
    <SecondComponentMain/>
    <CarouselComponent/>
    <NumberComponent/>
    <BlogComponent/>

    
  </div>
    
  
</template>

<script>
import  HeaderComponent       from "./components/HeaderComponent.vue";
import  MainContentHeader     from "./components/MainContentHeader.vue";
import  CoursesComponent      from "./components/CoursesComponent.vue";
import  SecondComponentMain   from "./components/SecondComponentMain.vue";
import  CarouselComponent     from "./components/CarouselComponent.vue";
import  NumberComponent       from "./components/NumberComponent.vue";
import  BlogComponent         from "./components/BlogComponent.vue";


export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainContentHeader,
    CoursesComponent,
    SecondComponentMain,
    CarouselComponent,
    NumberComponent,
    BlogComponent,
   
  }
}
</script>

<style lang="scss">
@import'~@fortawesome/fontawesome-free/css/all.css';


</style>
