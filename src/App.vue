<template>
  <v-container fluid class="min-h-screen w-100 bc overflow-hidden ">
    <v-sheet style="background-color:#040426" class="h-70 d-flex text-white mb-4 pa-4 justify-space-between content ">
      <p class="port "><v-icon icon="mdi-moon-waning-crescent bg-green-darken-4 rounded-circle pa-4 mr-4"></v-icon>PORTFOLIO</p>
      <div class="d-none d-sm-flex ga-4">
        <v-icon icon="mdi-home-circle" class="bg-green-darken-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
        <v-icon icon="mdi-tools" class="bg-green-darken-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
        <v-icon icon="mdi-school" class="bg-green-darken-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
        <v-icon icon="mdi-briefcase" class="bg-green-darken-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
        <v-icon icon="mdi-message" class="bg-green-darken-4 pa-4 text-subtitle-2 rounded-circle "></v-icon>
      </div>
    </v-sheet>

    <v-row no-gutters >
    <SideBar/>
    <v-col lg="9 content" md="9 content" sm="12">
    <IntroSection/>
    <ServicesSection/>
    <EducationSection/>
    <WorkSection/>
    <ContactSection/>
    <div class="bc text-grey-darken-2 d-flex pa-4  justify-center text-center mt-3">
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
.bc{
  background-color: #040426;
}
.port {
  letter-spacing: 1ch;
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {

}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {

}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  
 
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .side {
    position: fixed;
     top: 0;
    left: 0;
    height: 100vh;
    overflow-y: scroll;
         /* WebKit scrollbar customization */
         scrollbar-width: thin; /* For Firefox, adjust scrollbar width (optional) */
         scrollbar-color: #040426; /* For Firefox, change thumb and track color (optional) */
     
         /* For WebKit-based browsers */
         &::-webkit-scrollbar {
             width: 8px; /* Width of the scrollbar */
        
         }
     
         &::-webkit-scrollbar-track {
             background: green; /* Background color of the scrollbar track */
         }
     
         &::-webkit-scrollbar-thumb {
             background-color: #040426; /* Color of the scrollbar thumb */
             border:1px solid green; /* Spacing between thumb and track */
         }
   
  }
  
  .content{
    margin-left: 25%;
  }
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  .side {
    position: fixed;
     top: 0;
    left: 0;
    height: 100vh;
    overflow-y: scroll;

      /* WebKit scrollbar customization */
      scrollbar-width: thin; /* For Firefox, adjust scrollbar width (optional) */
      scrollbar-color: #040426; /* For Firefox, change thumb and track color (optional) */
  
      /* For WebKit-based browsers */
      &::-webkit-scrollbar {
          width: 8px; /* Width of the scrollbar */
     
      }
  
      &::-webkit-scrollbar-track {
          background: green; /* Background color of the scrollbar track */
      }
  
      &::-webkit-scrollbar-thumb {
          background-color: #040426; /* Color of the scrollbar thumb */
          border:1px solid green; /* Spacing between thumb and track */
      }
  
  }
  .content{
    margin-left: 25%;
  }
}
</style>
