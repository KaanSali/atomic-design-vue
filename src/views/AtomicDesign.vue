<template>
<div>
  <div class="flex justify-between w-auto">
      <ADButton btnText="Atomic" class="bg-blue-500 w-[150px]"/>
      <ADButton btnText="Design" class="bg-red-500 w-auto"/>
      <ADButton btnText="Button" class="bg-green-500 w-auto"/>
      <FigmaButton/>
  </div>
  <div class="flex">
      <UserLogin/>
  </div>
  </div>

</template>

<script>
import FigmaButton from '@/components/atoms/FigmaButton.vue'
import ADButton from '@/components/atoms/ADButton.vue';
import UserLogin from '@/components/molecule/UserLogin.vue'
export default {
    name:'AtomicDesign',
    components:{
        ADButton,
        FigmaButton,
        UserLogin
    }
}


</script>

<style>

</style>