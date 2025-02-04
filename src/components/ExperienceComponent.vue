<template>
    <div class="d-flex justify-content-center" id="experience">
        <h3 class="skills-heading mb-4">EXPERIENCE</h3>
    </div>
    <div class="d-flex justify-content-center">
        <div class="experince-container col-10 rounded shadow">
            <div class="text-container">
                <ul class="experience-list">
                    <li class="experience-row">
                        <div class="marker">
                            <div class="dot"></div>
                            <div class="line"></div>
                        </div>
                        <div class="experience-text">
                            <p class="year">2023 - Present</p>
                            <p class="experience-institute">Finahub Technology Solutions</p>
                            <h5>Software Engineer</h5>
                            <p>Developed and deployed 20+ RESTful APIs using Spring Boot, optimizing data exchange and
                                reducing code complexity by 25%. Improved maintainability through DeepSource analysis,
                                code reviews, and best practices. Created detailed API documentation, cutting support
                                requests by 25%. Enhanced system stability with automated tests (JUnit, Mockito) and
                                rigorous UAT, leading to a 15% reliability boost. Deployed scalable Java applications on
                                AWS (Tomcat) with a 20% performance gain. Strengthened user experience by modernizing
                                web interfaces with Vue.js and JavaScript, increasing customer satisfaction by 20%.</p>
                            <br>
                        </div>
                    </li>
                    <li class="experience-row">
                        <div class="marker">
                            <div class="dot"></div>
                            <div class="line"></div>
                        </div>
                        <div class="experience-text">
                            <p class="year">2022 - 2023</p>
                            <p class="experience-institute">Finahub Technology Solutions</p>
                            <h5>Java Full Stack Development Intern</h5>
                            <p>Developed 10+ Java applications, improving code efficiency by 20% and achieving a 99%
                                unit test success rate. Built 5+ responsive web pages with HTML and CSS, reducing page
                                load time by 10%. Wrote clean, functional code under expert guidance and enhanced system
                                performance by 35% by identifying and fixing critical bugs.</p>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>
<style>
.experince-container {
    background-color: white;
    color: #575757;
    padding: 3rem 3rem;
}

.text-container {
    text-align: left;
    font-size: small;
}

.year {
    color: #c1c1c2;
}

.experience-institute {
    margin-bottom: 0.7rem;
    font-weight: 550;
}

.experience-list {
    margin: 0;
    padding: 0;
}

ul p {
    margin-bottom: 0;
}

.experience-container {
    background-color: white;
    color: #858585;
    padding: 2rem 3rem;
}

h5 {
    font-weight: 600 !important;
}

.marker {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.dot {
    display: inline-block;
    width: 12px;
    height: 12px;
    background-color: transparent;
    border-radius: 50%;
    border: 3px solid #A6ADF0;
    margin-top: 5px;
}

.line {
    width: 0.5px;
    height: 100%;
    background-color: #c1c1c2;
    display: inline-block;

}

.experience-row {
    display: flex;
}

.experience-text {
    margin-left: 10px;
    display: inline-block;
}
</style>