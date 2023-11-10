<script   lang="ts">
import Greeting from './components/Greeting.vue';
import HelloWorld from './components/HelloWorld.vue'
const appWho = 'Vue.js'
export default {
  components: {
    HelloWorld
  },
  data () {
    return {
      appWho: 'Vue.js'
    }
  },
  methods: {
    setWho(newWho: string) {
      this.appWho = newWho
    }
  }
}
</script>

<template>
  <div id="app">
    <HelloWorld :msg="appWho" />
    <button @click="setWho('JavaScript')">JavaScript
      </button>
    <button @click="setWho('Everyone')">Everyone</button>
</div>
<div>
  <Greeting greeting="Hi" who="Everyone"/>
</div>
</template>

<style scoped>

  
</style>
