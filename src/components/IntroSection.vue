<template>
    <div>
        <p>Introduction</p>
        <p>{{ counter }}</p>
        <p v-if="counter >= 5">You have reached the limit</p>
        <button @click="increment">Increment</button>
        <ul>
            <li v-for="number in numbers" :key="number">{{ number }}</li>
        </ul>
        
    </div>
</template>

<script>
export default {
    name:'IntroSection',
    data() {
        return {
            counter:0,
            numbers:[1, 2, 3, 4]
        }
    },
    methods: {
        increment() {
            this.counter++
        }
    }
}
</script>

<style scoped>
ul {
    list-style: none;
    display:flex;
    justify-content: center;
}
li {
    margin:0 20px;
}
</style>