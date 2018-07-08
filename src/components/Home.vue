<template>
  <div>
    <h1 class="title">{{ msg }}</h1>
    <b>Safew Tech Labs</b> is a boutique software development company. We develop high quality,
        well tested, high performing and scalable products for the web, Android and iOS.
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Safew Tech Labs'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
