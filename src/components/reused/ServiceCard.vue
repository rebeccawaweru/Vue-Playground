<template>
    <div class="d-flex flex-column justify-center items-center w-100 h-100 mt-2 bg-white text-center pa-10 ga-2">
        <v-icon :icon="icn" class="align-self-center text-yellow-accent-4 text-h3"></v-icon>
        <p class="title">{{ title }}</p>
        <p class="text-grey-darken-2">{{ caption }}</p>
    </div>
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