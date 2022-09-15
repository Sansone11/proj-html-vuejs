<template>
  <MainHeader/>
  <MainContent/>
  <SectionOne/>
  <SectionTwo/>
  <SectionThree/>
  <SectionFour/>
  <SectionFive/>
  <SectionSix/>
  <SectionSeven/>
  <SectionEight/>
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
import SectionSix from './components/SectionSix.vue';
import SectionSeven from './components/SectionSeven.vue';
import SectionEight from './components/SectionEight.vue';

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
    SectionFive,
    SectionSix,
    SectionSeven,
    SectionEight
}
}
</script>

<style lang="scss">
#app {
 
}
</style>
