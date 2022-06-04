<script>
export default {
    props: {
        name: String
    }
}
</script>

<template>
    <h1>{{ name }}</h1>
</template>

<style>
h1 {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>