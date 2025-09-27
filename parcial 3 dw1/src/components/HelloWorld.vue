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
    <button @click="incrementar">+2</button>
    <button @click="decrementar">-2</button>
    <p>Contador: {{ count }}</p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
