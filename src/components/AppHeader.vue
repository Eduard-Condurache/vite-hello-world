<script>
export default {
  data() {
    return {
      message: 'Template Vite + Vue'

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
  margin-bottom: 14px;
  padding: 20px;
}

</style>
