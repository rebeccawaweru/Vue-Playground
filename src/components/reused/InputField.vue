<template>
    <label>{{ label }}</label>
    <input type="text" class="bg-grey-lighten-3"/>
</template>

<script>
export default {
    name:"InputField",
    props:{
        label:String,
    }
}
</script>

<style>
input {
    height: 8vh;
}
</style>