<template>
  <div class="home pt-24 text-xl text-gray-200">
    
    <HelloWorld msg="Coming soon"/>
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
