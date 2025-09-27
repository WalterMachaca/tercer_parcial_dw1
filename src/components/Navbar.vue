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
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #279157;
  padding: 10px;
  z-index: 1000;
}
ul {
  display: flex;
  gap: 100px;
  list-style: none;
    margin: 20px;
    padding: 0;
    font-size: 24px;    

}
a {
  color: white;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
</style>
