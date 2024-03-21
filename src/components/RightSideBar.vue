<template>
    <div>
        <p>Right Side</p>
        <p>{{ counter }}</p>
        <button @click="decrement">Decrement</button>
    </div>
</template>

<script>
export default {
    name:'RightSideBar',
    data() {
        return {
           counter:0
        }
    },
    methods:{
        decrement(){
            this.counter--
        }
    }
}
</script>