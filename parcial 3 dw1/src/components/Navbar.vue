<template>
  <nav class="navbar">
    <ul>
      <li><router-link to="/">Inicio</router-link></li>
      <li><router-link to="/contador">Contador</router-link></li>
    </ul>
  </nav>
</template>

<script setup>

</script>

<style scoped>
.navbar {
  background-color: #2c3e50;
  padding: 10px;
}
ul {
  display: flex;
  gap: 15px;
  list-style: none;
}
a {
  color: white;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
</style>
