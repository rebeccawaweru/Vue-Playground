<template>
    <v-row no-gutters>
    <v-col lg="3" sm="12">
      <p class="mb-3 title">{{ location }}</p>
      <span class="bg-yellow-accent-4 pa-2">{{ year }}</span>
    </v-col>
    <v-col lg="9" sm="12">
     <p class="title">{{ title }}</p>
     <p class="text-grey-darken-1">{{ desc }}</p>
    </v-col>
    </v-row>
</template>

<script>
export default {
    name:"ExperienceCard",
    props:{
        location:String,
        year:String,
        title:String,
        desc:String
    }
}
</script>