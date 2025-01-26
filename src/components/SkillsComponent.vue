<template>
    <div class="d-flex justify-content-center">
        <h3 class="skills-heading mb-4">SKILLS</h3>
    </div>
    <div class="d-flex justify-content-center">

        <div class="skills-container">
            <div class="shadow rounded">
                <img :src="require('@/assets/java.svg')">
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/springboot.svg')">
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/rest-api-icon.svg')">
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/mysql-official.svg')">
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/html-1.svg')">
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/css-3.svg')">
            </div>
            <div class="shadow rounded">
                <img :src="require('@/assets/aws-2.svg')">
            </div>
        </div>


    </div>
</template>
<style>

.skills-container div {
    display: flex;
    justify-content: center;
}

.skills-container img {
    width: 70px;
    /* padding: 1rem; */
    margin: 1rem;
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