<template>
    <div class="d-flex justify-content-center" id="education">
        <h3 class="skills-heading mb-4">PROJECTS</h3>
    </div>
    <div class="projects-section d-flex justify-content-center">
        <div class="projects-section-container col-10">
            <ProjectsComponent />
            <ProjectsComponent />
            <ProjectsComponent />
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
    margin-bottom: 50px;
}

.projects-section-container {
    display: flex;
    align-items: center;
    gap: 1rem;
    
}

</style>