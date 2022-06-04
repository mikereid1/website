<script>
import JSConfetti from 'js-confetti'
const jsConfetti = new JSConfetti()

export default {
    props: {
        name: String
    },
    methods: {
        confetti() {
            jsConfetti.addConfetti()
        }
    }
}
</script>

<template>
    <img @click="confetti" src="@/assets/me.png" alt="profile" width="125">
    <h1>{{ name }}</h1>
    <h3>Software Engineer</h3>
    <ul>
        <li>Java</li>
        <li>Kotlin</li>
        <li>JavaScript</li>
        <li>Spring Boot</li>
        <li>Vue.js</li>
        <li>MySQL</li>
    </ul>
    <br>
    I am a software developer with several years of experience mainly on backend projects creating REST microservices.<br>
    I enjoy learning new things and currently I work as a backend developer for <a href="https://www.spreadgroup.com">Spread Group</a>.
    <br>
    <br>
    <address>
        <a href="https://proton.me/">Email</a><br>
        <a href="https://www.linkedin.com/">LinkedIn</a><br>
        <a href="https://github.com/">GitHub</a><br>
    </address>
</template>

<style>
</style>