<template>
  <div class="home">
    <img alt="MJW logo" src="../assets/mjw.png">
    <HelloWorld msg="Marijuana Weight Coin"/>
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
