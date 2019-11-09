<template>
  <div class="home">
    <HelloWorld :msg="header"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  },
  data () {
    return {
      header: 'Welcome to TimeCard'
    }
  }
}
</script>
