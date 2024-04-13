<template>
    <v-sheet style="background-color:#040426" class="h-70 d-flex text-white mb-4 pa-4 justify-space-between content nav">
        <p class="port "><v-icon icon="mdi-home-account bg-green-darken-4 rounded-circle pa-4 mr-4"></v-icon>PORTFOLIO</p>
        <div class="d-none d-sm-flex ga-4">
          <NavIcon id="#home" icn="mdi-home-circle"/>
          <NavIcon id="#services" icn="mdi-tools"/>
          <NavIcon id="#education" icn="mdi-school"/>
          <NavIcon id="#experience" icn="mdi-briefcase"/>
          <NavIcon id="#contact" icn="mdi-message"/>
        </div>
      </v-sheet>
</template>

<script>
import NavIcon from './reused/NavIcon'
export default {
    name:"TopNav",
    components:{
        NavIcon
    }
}
</script>

<style>

</style>