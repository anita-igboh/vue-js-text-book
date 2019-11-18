<template>
  <div class="about">
    <h1>This is an about page</h1>
    <h1>{{ $store.state.hello }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Hello',
  data() {
    return {
      hi: 'Hello world'
    }
  },
  mounted() {
    console.log(this.$store.state.hello)
  }
}
</script>

<style scoped>
h1 {
  color:blue;
}
</style>