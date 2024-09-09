<script>

import AppHeader from './components/AppHeader.vue';

export default {
  data() {
    return {
      count: 0

    }
  },
  components: {
    AppHeader
  },
  methods: {
    incrementCount() {
      this.count++;
    }
  } 
}
</script>

<template>
  <div>
    <AppHeader/>
    <main>
      <button @click="incrementCount()">
        {{ count }}
      </button>
    </main>
  </div>
</template>

<style scoped>

main {
  text-align: center;
}

main button {
  padding: 14px;
  background-color: lightcoral;
  border: none;
  border-radius: 14px;
}

</style>
