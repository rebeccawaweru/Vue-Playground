<template>
  <v-container id="home" fluid class="min-h-screen w-100 bc overflow-hidden ">
    <TopNav/>
    <v-row no-gutters>
    <SideBar/>
    <v-col lg="9 content mt-16" md="9 content mt-16" sm="12">
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
import TopNav from './components/TopNav'
export default {
  name: 'App',
  components: {
    SideBar,
    IntroSection,
    ServicesSection,
    EducationSection,
    WorkSection,
    ContactSection,
    TopNav
  }
}
</script>

<style>
body{
       scroll-behavior: smooth;
       /* WebKit scrollbar customization */
       scrollbar-width: thin; /* For Firefox, adjust scrollbar width (optional) */
       scrollbar-color: #040426; /* For Firefox, change thumb and track color (optional) */
   
       /* For WebKit-based browsers */
       &::-webkit-scrollbar {
      
           width: 5px; /* Width of the scrollbar */
      
       }
   
       &::-webkit-scrollbar-track {
           background: #040426; /* Background color of the scrollbar track */
       }
   
       &::-webkit-scrollbar-thumb {
           background-color: transparent; /* Color of the scrollbar thumb */
           border:1px solid green; /* Spacing between thumb and track */
       }
   
}
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
.nav {
  width:74%;
  top: 0;
  position: fixed;
  align-items: center;
  z-index: 50;
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
   .nav {
    width:100%
   }
   .side {
    margin-top: 10%;
  }
  .profile {
    height:480px;
   }
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
  .nav {
    width:100%;
    margin-left: 0%;
  }
  .side {
    margin-top: 10%;
  }
  .profile {
    height: 480px;
   }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .nav {
    width:100%;
    margin-left: 0%;
  }
  .side {
    margin-top: 10%;
  }
  .profile {
    height: 480px;
   }

}

<!-- @media only screen and (min-width: 930px) {
  .nav {
    width:100%;
    margin-left: 0%;
  }
  .side {
    margin-top: 10%;
  }
  .profile {
    height: 480px;
   }
} -->
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 960px) {
  .side {
    margin-top: 0%;
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
              background: #040426; /* Background color of the scrollbar track */
          }
      
          &::-webkit-scrollbar-thumb {
              background-color: green; /* Color of the scrollbar thumb */
              border:1px solid green; /* Spacing between thumb and track */
          }
      
   
  }
  
  .content{
    margin-left: 25%;
  }
  .nav {
    width:74%
   }
   .profile {
    height: 480px;
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
          background: #040426; /* Background color of the scrollbar track */
      }
  
      &::-webkit-scrollbar-thumb {
          background-color: green; /* Color of the scrollbar thumb */
          border:1px solid green; /* Spacing between thumb and track */
      }
  
  }
  .content{
    margin-left: 25%;
  }
  .profile {
    height:480px;
   }
}

@media only screen and (min-width: 1700px) {
  .profile {
    height:780px;
   }
}
</style>
