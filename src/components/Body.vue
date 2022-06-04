<script>
import JSConfetti from 'js-confetti'
const jsConfetti = new JSConfetti()

export default {
    name: 'Body',
    methods: {
        confetti() {
            jsConfetti.addConfetti()
        }
    },
}
</script>

<template>
    <img @click="confetti" src="@/assets/me.png" alt="profile" width="125">
    <h3>Software Engineer</h3>
    <ul>
        <li>Java</li>
        <li>Kotlin</li>
        <li>Spring Boot</li>
        <li>JavaScript</li>
        <li>Vue.js</li>
        <li>MySQL</li>
    </ul>
    <br>
    I am a software developer with several years of experience mainly working on backends creating REST microservices.<br>
    I enjoy learning new things and currently I work as a backend developer for <a href="https://www.spreadgroup.com">Spread Group</a>.
    <br>
    <br>
</template>

<style>
</style>