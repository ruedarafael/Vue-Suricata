<template lang="">
  <nav class="navbar navbar-expand-lg navbar-light fixed-top">
    <div class="container px-4">
      <a class="navbar-brand" href="#"><img src="../assets/logo.png" alt="logo de suricata" /></a>
      <button class="navbar-toggler navbar-dark border-light" type="button" data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item active">
            <router-link :to="{ name:'inicio' }" class="nav-link text-light">Inicio</router-link>
            
          </li>
          <li class="nav-item">
            <router-link :to="{ name:'productos' }" class="nav-link text-light">Productos</router-link>
          </li>
          <li class="nav-item">
            <router-link :to="{ name:'contacto' }" class="nav-link text-light">Contacto</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>

export default {

}
</script>
<style scoped></style>