<template>
    <div class="d-flex justify-content-center" id="education">
        <h3 class="skills-heading mb-4">PROJECTS</h3>
    </div>
    <div class="projects-section d-flex justify-content-center">
        <ProjectsComponent />
        <ProjectsComponent />
        <ProjectsComponent />
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
    display: flex;
    margin-bottom: 50px;
    gap: 1rem;
}
</style>