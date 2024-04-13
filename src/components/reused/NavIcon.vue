<template>
    <a :href="id">
    <v-icon :icon="icn" class="bg-green-darken-4 pa-4 text-subtitle-2 rounded-circle"></v-icon>
    </a>
</template>

<script>
export default {
    name:"NavIcon",
    props: {
        id:String,
        icn:String
    }
}
</script>

