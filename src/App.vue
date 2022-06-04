<script>
import Header from './components/Header.vue'
import JSConfetti from 'js-confetti'

const confetti = new JSConfetti()

export default {
  components: {
    Header
  },
  data() {
    return {
      name: "Michael Reid"
    }
  },
  mounted() {
    confetti.addConfetti()
  }
}
</script>

<template>
  <Header :name="name" />
</template>

<style>
.Header {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>