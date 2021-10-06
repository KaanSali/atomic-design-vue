<template>
  <div class="rounded-xl grid grid-cols-2 border-2 p-6 w-4/12 m-auto mt-24">
      <RoundedImage src="https://images.pexels.com/photos/220453/pexels-photo-220453.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" class="mb-4  col-span-2"/>
      <ADButton btnText="Giriş Yap" class="bg-green-500 "/>
      <ADButton btnText="Kayıt Ol" class="bg-red-500 hover:bg-white hover:text-red-500 hover:ring-0 hover:border-red-500 hover:border-2 transition-all duration-300 h-[50px]"/>
      
  </div>
</template>

<script>
import ADButton from '@/components/atoms/ADButton.vue';
import RoundedImage from '@/components/atoms/RoundedImage.vue'

export default {
    name:'UserLogin',
    components:{
        ADButton,
        RoundedImage
    }
}
</script>

<style>

</style>