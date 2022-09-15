<template>
  <MainHeader/>
  <MainContent/>
  <SectionOne/>
  <SectionTwo/>
  <SectionThree/>
  <SectionFour/>
  <SectionFive/>
  <MainFooter/>
</template>

<script>
import MainHeader from './components/MainHeader.vue';
import MainContent from './components/MainContent.vue';
import MainFooter from './components/MainFooter.vue';
import SectionOne from './components/SectionOne.vue';
import SectionTwo from './components/SectionTwo.vue';
import SectionThree from './components/SectionThree.vue';
import SectionFour from './components/SectionFour.vue';
import SectionFive from './components/SectionFive.vue';

export default {
  name: 'App',
  components: {
    MainHeader,
    MainContent,
    MainFooter,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    SectionFive
}
}
</script>

<style lang="scss">
#app {
 
}
</style>
