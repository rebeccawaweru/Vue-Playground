<template>
    <div>
        <div class="d-flex justify-space-between">
            <p>{{ skill }}</p>
            <p>{{ level }}</p>
        </div>
        <div class="mt-2 divider"></div>
    </div>
</template>

<script>
export default {
    name:"SkillCard",
    props:{
        skill:String,
        level:String
    }
}
</script>