<template>
    <button class="approveBtn tracking-widest text-lg hover:ring-4 transition-shadow justify-self-center col-span-1 w-auto" type="submit"><span class="iconify" data-icon="mdi:account"></span>{{btnText}}</button>
</template>

<script>
export default {
    name:"ADButton",
    props: {
        btnText : String,
        btnColor: String
    }
}
</script>

<style>
.approveBtn{
    @apply flex items-center justify-center rounded-md  text-white font-bold p-3 px-4 ;
}
</style>