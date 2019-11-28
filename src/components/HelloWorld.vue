<template>
  <div class="text-center text-center">
    <h1>{{ msg }}</h1>
    <p class="text-5xl">
      Hashframe
    </p>
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

</style>
