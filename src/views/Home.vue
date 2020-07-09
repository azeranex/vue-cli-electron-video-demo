<template>
  <div class="home">
    <video width="320" height="240" controls>
      <source src="Holy - 35006.mp4" type="video/mp4">
    </video>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

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
