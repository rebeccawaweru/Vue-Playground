<template>
<v-row class="mt-8">
    <v-col class="d-flex flex-column ga-4">
        <p class="text-h6 font-weight-bold">Get In Touch</p>
        <div class="d-flex flex-column ga-6 pa-6 bg-white">
            <InputField label="Full Name"/>
            <InputField label="Email Address"/>
            <InputField label="Subject"/>
            <p>Message</p>
            <textarea cols="5" rows="6" class="bg-grey-lighten-3 w-100"></textarea>
            <v-btn class="bg-yellow-accent-4">SEND MESSAGE</v-btn>
        </div>
    </v-col>

    <v-col class="d-flex flex-column ga-5">
        <p class="text-h6 font-weight-bold">Contact Information</p>
        <div class="d-flex flex-column ga-4 pa-4 bg-white">
            <v-icon icon="mdi-map" class="bg-yellow-accent-4 pa-8 rounded-circle align-self-center"></v-icon>
            <InfoCard title="Country" caption="Kenya"/>
            <InfoCard title="Address" caption="P.O Box 1068-0509"/>
            <InfoCard title="City" caption="Nairobi, Kenya"/>
        </div>
        <div class="d-flex flex-column ga-4 pa-4 bg-white">
            <v-icon icon="mdi-email" class="bg-yellow-accent-4 pa-8 rounded-circle align-self-center"></v-icon>
            <InfoCard title="Email" caption="angelarobb37@gmail.com"/>
            <InfoCard title="Skype" caption="@yourusername"/>
            <InfoCard title="Telegram" caption="@yourusername"/>
        </div>
        <div class="d-flex flex-column ga-4 pa-4 bg-white">
            <v-icon icon="mdi-cellphone" class="bg-yellow-accent-4 pa-8 rounded-circle align-self-center"></v-icon>
            <InfoCard title="Office" caption="+254 726 850 377"/>
            <InfoCard title="Personal" caption="+254 726 850 377"/>
        </div>
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