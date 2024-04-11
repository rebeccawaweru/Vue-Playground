<template>
    <div class="d-flex justify-space-between text-white">
        <p>{{ title }}:</p>
        <p>{{ caption }}</p>
    </div>
</template>

<script>
export default {
    name:"InfoCard",
    props: {
        title: String,
        caption: String
    }
}
</script>