<template>
  <div id="app">
    <HeaderComponent/>
    <MainContentHeader/>
    <CoursesComponent/>
    <SecondComponentMain/>
    <CarouselComponent/>
    <NumberComponent/>
    <BlogComponent/>
    <SubscriveComponent/>

    
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
import  SubscriveComponent    from "./components/SubscriveComponent.vue";


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
    SubscriveComponent
   
  }
}
</script>

<style lang="scss">
@import'~@fortawesome/fontawesome-free/css/all.css';


</style>
