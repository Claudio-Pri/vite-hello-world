<script>
  export default {
  data() {
    return { 
      message: 'vite + vue'
     }
  },
}
</script>

<template>
  <header>
    <h1>
      {{ message }}
    </h1>
  </header>
</template>

<style scoped>
header {
  background-color: aqua;
  text-align: center;
}
h1 {
  color: white;
}
</style>
