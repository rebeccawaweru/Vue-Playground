<template>
    <div class="text-center d-flex flex-column align-items-center">
        <p class="mt-8 text-h6 font-weight-bold">My Services</p>
        <p class="w-50 text-grey-darken-1 align-self-center text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, voluptate at? Sint, aperiam rem culpa asperiores quia veniam error mollitia.</p>
      </div>
      <v-row>
        <v-col><ServiceCard icn="mdi-toolbox" title="Business Development" caption="Identify Possible Market Leads"/></v-col>
        <v-col><ServiceCard icn="mdi-invoice-multiple-outline" title="Project Management" caption="Implementing Project Processes"/></v-col>
        <v-col><ServiceCard icn="mdi-swap-vertical-variant" title="Customer Relations" caption="Proactive Client Engagement"/></v-col>
      </v-row>
      <v-row>
        <v-col><ServiceCard icn="mdi-ruler-square-compass" title="Logistics" caption="Logistic operations"/></v-col>
        <v-col><ServiceCard icn="mdi-briefcase-check" title="Microsoft Office" caption="Office Tools, CRM, Office 365"/></v-col>
        <v-col><ServiceCard icn="mdi-human-greeting-proximity" title="Communication" caption="Source and Identify Possible Market Leads"/></v-col>
      </v-row>
      <v-row>
        <v-col><ServiceCard icn="mdi-account-group" title="Team Work" caption="Coaching, Mentoring and Supporting Teams"/></v-col>
        <v-col><ServiceCard icn="mdi-microphone" title="Monitoring" caption="Monitoring and evaluating all project activities in the field"/></v-col>
        <v-col><ServiceCard icn="mdi-human-capacity-increase" title="Relationship Management" caption="Grow strong relationships/partnerships with clients"/></v-col>
      </v-row>
</template>

<script>
import ServiceCard from './reused/ServiceCard.vue';
export default {
    name:"ServicesSection",
    components:{
        ServiceCard
    }
}
</script>
