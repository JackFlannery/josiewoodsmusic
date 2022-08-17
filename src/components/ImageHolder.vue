<template>
  <div class="imageHold">
    <img :src="require('../assets/' + url)" />
  </div>
</template>

<script>
export default {
  name: 'ImageHolder',
  props: {
    url: String
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.imageHold {
    v-bind:style="";
    position: relative;
}

</style>
