<template>
  <SideBar/>
  <IntroSection/>
  <RightSideBar/>
</template>
<script>

import SideBar from './components/SideBar.vue'
import IntroSection from './components/IntroSection.vue'
import RightSideBar from './components/RightSideBar.vue'

export default {
  name: 'App',
  components: {
    SideBar,
    IntroSection,
    RightSideBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
