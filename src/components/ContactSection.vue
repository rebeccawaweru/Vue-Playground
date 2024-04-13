<template>
<v-row id="contact" class="mt-8 text-white">
    <v-col class="d-flex flex-column ga-4 pa-6">
        <p class="port text-left">LET'S TALK</p>
        <div style="width: 10%;" class="my-2 divider "></div>
        <div class="d-flex flex-column ga-7 bc">
            <InputField label="Full Name"/>
            <InputField label="Email Address"/>
            <InputField label="Subject"/>
            <label class="text-grey-lighten-3">Message</label>
            <textarea cols="5" rows="7" class="bg-grey-lighten-3 w-100"></textarea>
            <v-btn class="bg-green-darken-4">SEND MESSAGE</v-btn>
        </div>
    </v-col>

    <v-col class="d-flex flex-column ga-5">
        <p class="port text-left">CONTACT INFO</p>
        <div style="width: 10%;" class="my-2 divider "></div>
        <v-sheet style="background-color:#040426" border="success md" class="d-flex flex-column ga-4 pa-4 bc">
            <v-icon icon="mdi-map" class="bg-green-darken-4 pa-8 rounded-circle align-self-center"></v-icon>
            <InfoCard title="Country" caption="Kenya"/>
            <InfoCard title="Address" caption="P.O Box 1068-0509"/>
            <InfoCard title="City" caption="Nairobi, Kenya"/>
        </v-sheet>
        <v-sheet style="background-color:#040426" border="success md" class="d-flex flex-column ga-4 pa-4 bc">
            <v-icon icon="mdi-email" class="bg-green-darken-4 pa-8 rounded-circle align-self-center"></v-icon>
            <InfoCard title="Email" caption="angelarobb37@gmail.com"/>
            <InfoCard title="Skype" caption="@yourusername"/>
            <InfoCard title="Telegram" caption="@yourusername"/>
        </v-sheet>
        <v-sheet style="background-color:#040426" border="success md" class="d-flex flex-column ga-4 pa-4 bc">
            <v-icon icon="mdi-cellphone" class="bg-green-darken-4 pa-8 rounded-circle align-self-center"></v-icon>
            <InfoCard title="Office" caption="+254 726 850 377"/>
            <InfoCard title="Personal" caption="+254 726 850 377"/>
        </v-sheet>
    </v-col>
</v-row>
</template>

<script>
import InfoCard from './reused/InfoCard.vue'
import InputField from './reused/InputField.vue';
export default {
    name:"ContactSection",
    components:{
        InfoCard,
        InputField
    }
}
</script>