<script>
/*
Passaggi import componente:
1) Importazione componente
2) Dichiarazione del componente
3) Utilizzo del componente
*/

// 1) Importazione componente
import AppHeader from './components/AppHeader.vue';

  export default {
  data() {
    return { 
      count: 0
     }
  },
  //2) Dichiarazione del componente (prima o dopo data())
  components: {
    AppHeader
  },
  methods: {
    incrementCount() {
      this.count++;
    }
  }
}
</script>

<template>
  <!-- N.B. Template vuole 1 solo figlio -->
  <div>
    <!-- 3) Utilizzo del componente come tag htm (self-closing) -->
    <AppHeader/>
    <button @click="incrementCount()">
      {{ count }}
    </button>
  </div>
</template>

<style scoped>

</style>
