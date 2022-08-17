<template>
  <div class="home">
    <ImageHolder url="jrfsmilesixtext.png"/>
    <HelloWorld msg="Suck on Lemons!"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import ImageHolder from '@/components/ImageHolder.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    ImageHolder
  }
}
</script>

