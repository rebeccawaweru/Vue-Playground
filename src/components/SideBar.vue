<template>
    <v-col lg="3" md="3"  sm="12" class="side" >
        <v-sheet style="background-color:#040426" class="text-white pa-4 mr-2 d-flex flex-column justify-center items-center ga-6">
        
            <v-img style="border: 1px green solid"  :src="require('../assets/new-angiee.png')"  :width="150" :height="145" cover  class="rounded-circle align-self-center prof"> </v-img>
        <p class="text-center">ANGELA J. ROBB</p>
        <p class="text-grey-lighten-1 text-center">Business Administrator</p>
        <v-divider :thickness="1"></v-divider>
      
        <div class="d-flex flex-column ga-4">
        <InfoCard title="Phone" caption="+254 726 850 377"/>
        <InfoCard title="Email" caption="angelarobb37@gmail.com"/>
        <!-- <InfoCard title="Employ" caption="Available"/> -->
        <InfoCard title="Address" caption="Nairobi, Kenya"/>
        </div>

        <v-divider :thickness="1"></v-divider>
        <div class="d-flex flex-column ga-4">
        <p class="text-h6 font-weight-bold">Languages</p>
        <SkillCard skill="English" level="100%"/>
        <SkillCard skill="Kiswahili" level="100%"/>     
        </div>

     
        <div class="d-flex flex-column ga-4">
        <p class="text-h6 font-weight-bold">Skills</p>
        <SkillCard skill="Logistics" level="90%"/>
        <SkillCard skill="Microsoft Office" level="100%"/>     
        <SkillCard skill="Business Development" level="95%"/>  
        <SkillCard skill="Customer Relations" level="100%"/>  
        <SkillCard skill="Accounting" level="90%"/>  
        </div>
        <div class="d-flex flex-column ga-4">
            <p class="text-h6 font-weight-bold">Extra Skills</p>
            <p><v-icon icon="mdi-code-block-brackets" class="text-green-darken-4 mr-2"></v-icon>Monitoring & Evaluation</p>
            <p><v-icon icon="mdi-code-block-brackets" class="text-green-darken-4 mr-2"></v-icon>Communication</p>
            <p><v-icon icon="mdi-code-block-brackets" class="text-green-darken-4 mr-2"></v-icon>Team Work</p>
            <p><v-icon icon="mdi-code-block-brackets" class="text-green-darken-4 mr-2"></v-icon>Adaptability</p>
        </div>
        <v-btn class="bg-green-darken-4" append-icon="mdi-download">DOWNLOAD CV </v-btn>
        </v-sheet>
      </v-col>

</template>

<script>
import InfoCard from './reused/InfoCard.vue'
import SkillCard from './reused/SkillCard.vue'
export default {
    name: 'SideBar',
    components:{
        InfoCard,
        SkillCard
    }
}
</script>

<style>

.bc{
    background-color: #0F0530;
  }    
 .divider {
   border: 2px green solid;
 }
</style>