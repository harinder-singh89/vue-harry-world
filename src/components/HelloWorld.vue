<template>
  <div class="hello">
    Hello World
    <p>{{title}}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props:{
    title: {
      default: "title test"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
