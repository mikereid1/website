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
    <div style="text-align: center">
        <img @click="confetti" src="@/assets/me.png" alt="profile" width="125" class="image">
        <h3>Software Engineer</h3>
        <div class="display: inline-block; ext-align: left;">
            <ul>
                <li>Java</li>
                <li>Kotlin</li>
                <li>Spring Boot</li>
                <li>JavaScript</li>
                <li>Vue.js</li>
                <li>MySQL</li>
            </ul>
        </div>
        <br>
        I am a software developer with several years of experience mainly working on backends creating REST
        microservices.<br>
        I enjoy learning new things and currently I work as a backend developer for <a
            href="https://www.spreadgroup.com">Spread Group</a>.
        <br>
        <br>
    </div>
</template>

<style scoped>
.image {
    border-radius: 50%;
    border: 5px solid #555;
}
</style>