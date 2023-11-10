<script   lang="ts">
export default {
  name: 'HelloWorld',
  props: ['msg']
  
}
  
</script>

<template>
  <div class="hello">
    <h1>Hello {{ msg }}</h1>
    <!-- … -->
  </div>

</template>

<style scoped>
.hello {
  color: blue;
}

</style>
