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
        <li>Mysql</li>
    </ul>
    <br>
    Hi *,<br>
    I am a software developer with several years of experience. I have worked mainly on backend projects creating REST
    microservices. I enjoy learning new things and currently I have the pleasure to work with people from whom I can
    learn so much.
    <br>
    <br>
    <address>
        <a href="michaelreid@email.com">Email</a><br>
        <a href="https://www.linkedin.com/in/myurl/">LinkedIn</a><br>
        <a href="https://github.com/myurl/">GitHub</a><br>
    </address>
</template>

<style>
</style>