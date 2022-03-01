<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div>
      <button @click="changeRouter" class="btn-primary">Botón primario</button>
    </div>
  </div>
</template>
<script>
export default {
  methods: {
    changeRouter() {
      this.$router.push({ name: 'no-entry'})
    }
  }
}
</script>
