<template>
    <div id="experience" class="text-center text-white d-flex flex-column align-items-center bc my-8">
        <p class="port">EXPERIENCE</p>
        <div style="width: 10%;" class="my-2 divider align-self-center"></div>
        <p class="w-50 text-grey-darken-1 align-self-center text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, voluptate at? Sint, aperiam rem culpa asperiores quia veniam error mollitia.</p>
      </div>
    <div class="bc text-white d-flex flex-column ga-6 mt-2 pa-4">
        <ExperienceCard location="Business Administrator" year="August 2022 - Present" title="Geosurveys And Geospatial Info Ltd" desc="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum, expedita, aperiam aspernatur nostrum facere hic minus consectetur dolorum harum illo esse beatae. Consequuntur nam ullam magni vitae laboriosam, minus qui."/>
        <v-divider :thickness="1"></v-divider>
        <ExperienceCard location="Business Development Manager" year="July 2021 - June 2022" title="X Ray Security & Tracking Ltd" desc="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum, expedita, aperiam aspernatur nostrum facere hic minus consectetur dolorum harum illo esse beatae. Consequuntur nam ullam magni vitae laboriosam, minus qui."/>
        <v-divider :thickness="1"></v-divider>
        <ExperienceCard location="Account Manager" year="July 2017 - May 2021" title="Borderless Tracking / Safetrac Ltd" desc="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum, expedita, aperiam aspernatur nostrum facere hic minus consectetur dolorum harum illo esse beatae. Consequuntur nam ullam magni vitae laboriosam, minus qui."/>
    </div>
</template>

<script>
import ExperienceCard from './reused/ExperienceCard.vue';
export default {
    name:"WorkSection",
    components:{
        ExperienceCard
    }

}
</script>