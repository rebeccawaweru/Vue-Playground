<template>
    <v-sheet border="success md" style="background-color:#040426"  class=" d-flex flex-column justify-center items-center w-100 h-100 mt-2 text-center pa-10 ga-2">
        <v-icon :icon="icn" class="align-self-center text-green-darken-4 text-h3"></v-icon>
        <p class="title text-white">{{ title }}</p>
        <p class="text-grey-darken-2">{{ caption }}</p>
    </v-sheet>
</template>

<script>
export default {
    name:"ServiceCard",
    props:{
        icn:String,
        title:String,
        caption:String
    }
}
</script>

<style>
.title{
  font-size: large;
}
</style>