<script>
  export default {
  data() {
    return { 
      message: 'template vite + vue'
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
  color: lawngreen;
}
</style>
