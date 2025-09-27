<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)

function incrementar() {
  count.value += 2
}

function decrementar() {
  count.value -= 2
}
</script>

<template>
  <h2>{{ msg }}</h2>
  <div class="card">
    <button @click="incrementar">Incrementar: +2</button>
    <button @click="decrementar">Decrementar: -2</button>
    <p>Contador: {{ count }}</p>
  </div>
</template>

<style scoped>
.card {
  margin-top: 100px;
}
button {
  background-color: #279157;
  margin: 20px;
  padding: 8px 15px;
  cursor: pointer;
}
p {
  font-size: 30px;
}
</style>
