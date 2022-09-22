<template>

  <div id="app">
    <HeaderComponent/>
    <SectionMainComponent/>
    <SecondSectionComponent/>
    <FooterComponent/>
    <SecondFooterComponent/>

  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import SectionMainComponent from './components/SectionMainComponent.vue';
import SecondSectionComponent from './components/SecondSectionCompotent.vue';
import FooterComponent from './components/FooterComponent.vue';
import SecondFooterComponent from './components/SecondFooterComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    SectionMainComponent,
    SecondSectionComponent,
    FooterComponent,
    SecondFooterComponent,
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
