<template>
  <div class="home">
    <img alt="Loftie Ellis" src="../assets/me.png">
    <HelloWorld msg="Loftie Ellis"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
