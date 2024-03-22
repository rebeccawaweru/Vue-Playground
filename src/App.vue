<template>
  <v-container fluid class="min-h-screen w-100 bg-grey-lighten-3 overflow-hidden ">
    <div class="h-70 w-100 d-flex bg-white mb-4 pa-4 justify-space-between">
      <p class="port d-none d-sm-block">PORTFOLIO</p>
      <div class="d-flex ga-4">
        <v-icon icon="mdi-home-circle" class="bg-yellow-accent-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
        <v-icon icon="mdi-tools" class="bg-yellow-accent-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
        <v-icon icon="mdi-school" class="bg-yellow-accent-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
        <v-icon icon="mdi-briefcase" class="bg-yellow-accent-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
        <v-icon icon="mdi-message" class="bg-yellow-accent-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
      </div>
   
    </div>
    <v-row no-gutters>
    <SideBar/>
    <v-col lg="9" md="9" sm="12" >
    <IntroSection/>
    <ServicesSection/>
    <EducationSection/>
    <WorkSection/>
    <ContactSection/>
    <div class="bg-white d-flex pa-4  justify-center text-center mt-3">
      <p>Copyright &copy; 2024 Angela J. Robb All Rights Reserved</p>
    </div>
    </v-col>
    </v-row>
  </v-container>
</template>

<script>
import SideBar from './components/SideBar'
import IntroSection from './components/IntroSection'
import ServicesSection from './components/ServicesSection'
import EducationSection from './components/EducationSection'
import WorkSection from './components/WorkSection'
import ContactSection from './components/ContactSection'
export default {
  name: 'App',
  components: {
    SideBar,
    IntroSection,
    ServicesSection,
    EducationSection,
    WorkSection,
    ContactSection
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
.port {
  letter-spacing: 1ch;
}
</style>
