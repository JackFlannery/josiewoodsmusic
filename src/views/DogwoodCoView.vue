<template>
  <div class="home">
    <img alt="Dogwood Co. Logo" src="../assets/dogwoodco.png">
    <HelloWorld msg="Dogwood Co."/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>