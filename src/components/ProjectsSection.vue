<template>
    <div class="d-flex justify-content-center" id="projects">
        <h3 class="skills-heading mb-4">PROJECTS</h3>
    </div>
    <div class="projects-section d-flex justify-content-center">
        <div class="projects-section-container col-10">
            <ProjectsComponent title="Design Patterns" url="https://github.com/Vysakh-vn/DesignPatterns"
                :tags="['java', 'oops']" description="Java implementations of various design patterns. Each pattern includes examples and use cases for
                easy understanding." />
            <ProjectsComponent title="portfolio-site" url="https://github.com/Vysakh-vn/portfolio-site"
                :tags="['vue-js', 'html', 'css']" description="My portfolio website, built using Vue.js.  It provides a showcase of my projects and experience." />
            <ProjectsComponent title="LeetCodeSolutions" url="https://github.com/Vysakh-vn/LeetCodeSolutions"
                :tags="['java', 'algorithms', 'data-structures']" description="Collection of Java solutions for LeetCode problems, emphasizing clean, efficient, and well-documented code implementations." />
        </div>
    </div>
</template>
<script>
import ProjectsComponent from './ProjectsComponent.vue';
export default {
    components: {
        ProjectsComponent
    }
}
</script>
<style scoped>
.projects-section {
    /* margin-bottom: 50px; */
}

.projects-section-container {
    display: flex;
    align-items: center;
    gap: 1rem;
    flex-wrap: wrap;
}
</style>