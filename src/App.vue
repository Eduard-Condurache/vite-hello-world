<script>

import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue'

export default {
  data() {
    return {}
  },
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div>
    <AppTitle/>
    <AppHero/>
    <main>
    </main>
  </div>
</template>

<style scoped></style>
