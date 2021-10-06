<template>
  <div>
    <div class="mx-auto">
      <img alt="Vue logo" src="../assets/logo.png">
    </div>
    <HelloWorld msg="Merhaba Minnoş Aşkım Umay Kaya"/>
  </div>
</template>
<style scoped>
img{
 @apply mx-auto;
}
</style>
<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
