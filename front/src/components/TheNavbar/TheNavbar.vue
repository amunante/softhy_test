<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid m-2">
      <button
        type="button"
        class="navbar-toggler"
        data-bs-target="#navbar"
        data-bs-toggle="collapse"
        aria-controls="navbar"
        aria-expanded="false"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="navbar-collapse collapse" id="navbar">
        <ul class="navbar-nav ms-auto mx-auto" >
          <li class="nav-item ms-auto">
            <router-link class='link-format p-sm-md-3' to="/estudiantes">Estudiantes</router-link>
          </li>
          <li class="nav-item ms-auto">
            <router-link class='link-format p-md-3' to="/pagos">Pagos</router-link>
          </li>
          <li class="nav-item ms-auto">
            <router-link class='link-format p-md-3' to="/reportes">Reportes</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script src='./index.js'>
</script>
<style scoped>
    @import './styles.css';
</style>