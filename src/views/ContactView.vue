<template>
  <div class="about">
    <h1>This is an about page</h1>
    <button @click="VolverAlInicio" class="btn btn-light">Ir a inicio</button>
  </div>
</template>
<script>
export default {
  methods: {
    VolverAlInicio() {
      this.$router.push({ name: 'inicio' }) 
    }
  }
}
</script>