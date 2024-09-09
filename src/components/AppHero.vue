<script>
export default {
  data() {
    return {}
  }
}
</script>

<template>
  <main>
    <div class="image-container">
      <img src="../assets/immagine.png" alt="imagine">
      <h1>
        Vue + Vite
      </h1>
    </div>
  </main>
</template>

<style scoped>
  .image-container {
    position: relative;
    text-align: center;
    color: white;
  }

  .image-container h1 {
    position: absolute;
    top: 10%;
    left: 50%;
    transform: translate(-50%, -50%); 
  }

</style>
