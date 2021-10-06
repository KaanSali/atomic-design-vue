<template>
  <div class="hello">
    <h1 class="text-2xl font-bold">{{ msg }}</h1>
    <p>
      Bugün seninle vue üzerinde "Atomic Design" ile ilgili bir çalışma gerçekleştireceğiz.<br/><br/>
      Bu konuyla ilgili çok faydalı olacak bir eğitim videosu buldum senin için, aşağıdaki linkten ulaşabilirsin <br/><br/> 
      <a href="https://www.youtube.com/watch?v=RYDiDpW2VkM" target="_blank" rel="noopener">Create a Design System with Figma - Full Course</a>
    </p>
    <h3>Hadi seninle boş bir sayfada çalışmaya başlayalım 😊😊</h3>
    <ul>
      <router-link to="/atomic-design">Atomic Design'a başlayalım</router-link>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
