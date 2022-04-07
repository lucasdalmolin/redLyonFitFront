
<template>
  <div class="container-nav" >
    <nav class="nav">
      <img src="" alt="logo">
        <ul>
          <li>PROFESOR</li>
          <li>PLANIFICACION DIARIA</li>
          <li>EJERCICIOS</li>
          <li>ENTREVISTAS</li>
          <li>DONA AQUI</li>
          <li>CREAR CUENTA</li>
        </ul>
    </nav>
  </div>
</template>

<style>

.nav{
  display: flex;
  background: black;
  height: 80px;
  align-items: center;
  justify-content: flex-end
}

.nav ul {
  display:flex;
  flex-direction: row;
  gap: 20px;
  justify-content: right;
}

.nav ul li {
  color: #ffff;
  list-style: none;
}

</style>

    <script setup>
    defineProps({
      msg: {
        type: String,
        required: true
      }
    })
    </script>