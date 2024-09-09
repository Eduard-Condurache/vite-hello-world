<script>
export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'

    }
  }
}
</script>

<template>
  <header>
    <h1>
      {{ message }}
    </h1>
  </header>
</template>

<style scoped>
header {
  background-color: lightgreen;
  text-align: center;
  padding: 20px;
}

</style>
