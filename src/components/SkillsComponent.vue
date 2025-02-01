<template>
    <div class="d-flex justify-content-center" id="skills">
        <h3 class="skills-heading mb-4">SKILLS</h3>
    </div>
    <div class="d-flex justify-content-center skills-content-container">

        <div class="skills-container">
            <div class="shadow rounded skill">
                <img :src="require('@/assets/java.svg')" alt="Java logo">
                <p>Java</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/springboot.svg')" alt="Spring boot logo">
                <p>Spring Boot</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/rest-api-icon.svg')" alt="REST logo">
                <p>REST API</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/mysql-official.svg')" alt="MySQL logo">
                <p>MySQL</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/html-1.svg')" alt="Html logo">
                <p>Html</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/css-3.svg')" alt="CSS logo">
                <p>CSS</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/javascript-1.svg')" alt="Javascript logo">
                <p>Javascript</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/bootstrap-5-1.svg')" alt="Bootstrap logo">
                <p>Bootstrap</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/vue-9.svg')" alt="Vue js logo">
                <p>Vue js</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/aws-2.svg')" alt="AWS logo">
                <p>AWS</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/figma-icon.svg')" style="width: 50px;" alt="Figma logo">
                <p>Figma</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/git-icon.svg')" alt="Git logo">
                <p>Git</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/github.svg')" alt="Github logo">
                <p>Github</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/postman.svg')" alt="Postman logo">
                <p>Postman</p>
            </div>
            <div class="shadow rounded skill">
                <img :src="require('@/assets/gradle-1.svg')" alt="Gradle logo">
                <p>Gradle</p>
            </div>
        </div>

    </div>
</template>
<style>

.skills-content-container {
    padding: 0 5% 0 5%;
}

.skills-container .skill {
    display: grid;
    grid-template-rows: 3fr 1fr;
    justify-content: center;
    align-items: center;
    color: #818181;
    font-size: 0.8rem;
    font-weight: 500;
    background-color: white;
    padding: 0.8%;
    transition: transform 0.3s ease-in-out;
}

.skills-container .skill:hover {
    transform: scale(1.1);
}

.skills-container img {
    width: 70px;
    margin: 0.5rem;
    margin-right: 2rem;
    margin-left: 2rem;
}

.skills-container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 1.5rem;
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