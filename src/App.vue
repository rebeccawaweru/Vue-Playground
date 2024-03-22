<template>
  <v-container fluid class="min-h-screen w-100 bg-grey-lighten-3 overflow-x-hidden ">
    <div class="h-70 w-100 bg-white mb-4">
     <p>Navbar</p>
    </div>
    <v-row no-gutters>
    <SideBar/>
    <v-col lg="9" sm="12">
    <IntroSection/>
    </v-col>
    </v-row>
  </v-container>
</template>

<script>
import SideBar from './components/SideBar.vue'
import IntroSection from './components/IntroSection.vue'


export default {
  name: 'App',
  components: {
    SideBar,
    IntroSection
  }
}
</script>

<style>
#app {
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
