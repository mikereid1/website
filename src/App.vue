<script>
import Header from './components/Header.vue'

export default {
  components: {
    Header
  },
  data() {
    return {
      name: "Michael Reid"
    }
  }
}
</script>

<template>
  <Header :name="name" />
</template>

<style>
</style>