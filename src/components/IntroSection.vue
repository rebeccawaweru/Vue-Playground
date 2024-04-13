<template>
    <v-sheet style="background-color:#040426" class="mt-2 text-white">
        <v-row>
         <v-col class="d-flex flex-column px-8 justify-center text-left ga-4">
            <span class="text-xs">Hello, I'm</span> 
           <p class="text-h3 font-weight-bold">ANGELA J. ROBB</p>
           <p class="text-h3 font-weight-bold"><span class="text-green-darken-4">Business</span> Administrator</p>
           <p class="text-grey-darken-2">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Accusamus dolor hic adipisci soluta. Quasi, facilis. Similique at consequuntur molestias dignissimos necessitatibus illo voluptates alias soluta omnis. Quos praesentium veritatis nostrum?</p>
           <v-btn size="x-large" class="bg-green-darken-4" append-icon="mdi-arrow-right-thin">HIRE ME</v-btn>
         </v-col>
         <v-col class="d-none d-sm-flex">
            <v-img :src="require('../assets/angie-new.png')"  class="rounded-circle align-self-center prof profile"> </v-img>

            <!-- <v-sheet class="profile"> </v-sheet> -->
         </v-col>
        </v-row>         
     </v-sheet>
    <!-- <div>
        <p>Introduction</p>
        <p>{{ counter }}</p>
        <p v-if="counter >= 5">You have reached the limit</p>
        <button @click="increment">Increment</button>
        <ul>
            <li v-for="number in numbers" :key="number">{{ number }}</li>
        </ul>
    </div> -->

</template>

<script>
export default {
    name:'IntroSection',
    // data() {
    //     return {
    //         counter:0,
    //         numbers:[1, 2, 3, 4]
    //     }
    // },
    // methods: {
    //     increment() {
    //         this.counter++
    //     }
    // }
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