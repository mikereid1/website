<script>
export default {
    name: 'Body',
    data() {
        return {
            name: "Michael Reid"
        }
    },
}
</script>

<template>
    <div class="center">
        <h1>{{ name }}</h1>
        <hr>
        <p>Software Engineer</p>
    </div>
</template>

<style scoped>
.center {
    text-align: center;
}
</style>