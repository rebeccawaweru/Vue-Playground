<template>
    <div class="text-center d-flex flex-column align-items-center">
        <p class="mt-8 text-h6 font-weight-bold">Education</p>
        <p class="w-50 text-grey-darken-1 align-self-center text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, voluptate at? Sint, aperiam rem culpa asperiores quia veniam error mollitia.</p>
      </div>
    <div class="bg-white d-flex flex-column ga-6 mt-2 pa-4">
        <ExperienceCard location="Masinde Muliro" year="2009 - 2016" title="Bachelor on Conflict Resolution" desc="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum, expedita, aperiam aspernatur nostrum facere hic minus consectetur dolorum harum illo esse beatae. Consequuntur nam ullam magni vitae laboriosam, minus qui."/>
        <v-divider :thickness="1"></v-divider>
        <ExperienceCard location="Ricatti Business College" year="2009" title="Microsoft Skills" desc="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum, expedita, aperiam aspernatur nostrum facere hic minus consectetur dolorum harum illo esse beatae. Consequuntur nam ullam magni vitae laboriosam, minus qui."/>
        <v-divider :thickness="1"></v-divider>
        <ExperienceCard location="Corporate Staffing" year="2018" title="Customer Service Training" desc="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum, expedita, aperiam aspernatur nostrum facere hic minus consectetur dolorum harum illo esse beatae. Consequuntur nam ullam magni vitae laboriosam, minus qui."/>
    </div>
</template>

<script>
import ExperienceCard from './reused/ExperienceCard.vue';
export default {
    name:"EducationSection",
    components:{
        ExperienceCard
    }

}
</script>