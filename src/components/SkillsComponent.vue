<template>
    <div class="d-flex justify-content-center">
        <h3 class="skills-heading mb-4">SKILLS</h3>
    </div>
    <div class="d-flex justify-content-center">

        <div class="skills-container">
            <div class="shadow rounded">
                <img :src="require('@/assets/java.svg')">
                <p>Java</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/springboot.svg')">
                <p>Spring Boot</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/rest-api-icon.svg')">
                <p>REST API</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/mysql-official.svg')">
                <p>MySQL</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/html-1.svg')">
                <p>Html</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/css-3.svg')">
                <p>CSS</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/aws-2.svg')">
                <p>AWS</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/javascript-1.svg')">
                <p>Javascript</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/bootstrap-5-1.svg')">
                <p>Bootstrap</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/vue-9.svg')">
                <p>Vue js</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/figma-icon.svg')" style="width: 50px;">
                <p>Figma</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/git-icon.svg')">
                <p>Git</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/github.svg')">
                <p>Github</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/postman.svg')">
                <p>Postman</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/gradle-1.svg')">
                <p>Gradle</p>
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/apache-maven-1.svg')">
                <p>Maven</p>
            </div>
        </div>


    </div>
</template>
<style>

.skills-container div {
    display: grid;
    grid-template-rows: 3fr 1fr;
    justify-content: center;
    align-items: center;
    color: #818181;
    font-size: 0.8rem;
    font-weight: 500;
    background-color: white;
}

.skills-container img {
    width: 70px;
    margin: 0.5rem;
    margin-right: 2rem;
    margin-left: 2rem;
}

.skills-container {
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    gap: 1rem;
}

@media (max-width: 768px) {
    .skills-container {
        grid-template-columns: repeat(4, 1fr);
    }
}

@media (max-width: 480px) {
    .skills-container {
        grid-template-columns: repeat(2, 1fr);
    }
}

.skills-heading {
    font-weight: 600;
    color: #818181;
    margin-top: 7rem;
}
</style>