<template>

  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
    <ShopAreaComponent/>
    <FooterComponent/>
    <SocialComponent/>

  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import ShopAreaComponent from './components/ShopAreaComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import SocialComponent from './components/SocialCompontent.vue';


export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    ShopAreaComponent,
    FooterComponent,
    SocialComponent,
    
}
}
</script>

<style lang="scss">
  *{
  margin: 0 auto;
  padding: 0;
  box-sizing: border-box;
 }


#app {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
