<template>

  <div class="container" id="about">

    <div class="d-flex justify-content-center">
      <div id="main-container" class="col-lg-10 col-md-10 col-10 rounded shadow">

        <ProfilePhoto />

        <h2 class="mt-3">VYSAKH V N</h2>
        <div class="text-container">
          <div class="d-flex">
            <img :src="require('@/assets/job.svg')">
            <p class="ms-2">Software Engineer</p>
          </div>

          <div class="d-flex">
            <img :src="require('@/assets/location.svg')">
            <p class="ms-2">Kerala, India</p>
          </div>

          <p>Software Engineer with 2 years of experience in designing, developing, and deploying robust applications.
            Skilled in Java and Spring Boot, with expertise in building 20+ RESTful APIs, optimizing code quality, and
            improving system stability. Proficient in version control and collaborating with cross-functional teams to
            deliver scalable solutions.</p>
          <!-- <button id="btn">Get in touch</button> -->

          <SocialMedia />
        </div>
      </div>
    </div>

    <SkillsComponent />
    <ExperinceComponent />
    <EducationComponent />

  </div>

</template>
<script>
import ProfilePhoto from './ProfilePhoto.vue'
import SocialMedia from './SocialMedia.vue'
import SkillsComponent from './SkillsComponent.vue'
import ExperinceComponent from './ExperienceComponent.vue'
import EducationComponent from './EducationComponent.vue'

export default {
  components: {
    ProfilePhoto, SocialMedia, SkillsComponent, ExperinceComponent, EducationComponent
  }
}
</script>

<style>
.text-container img {
  width: 1rem;
  height: 1rem;
}

#btn {
  border-radius: 50px;
  padding: 8px 20px;
  color: white;
  background-color: #A6ADF0;
  border: none;
  cursor: pointer;
  transition: #A6ADF0 0.3s ease;
  font-size: 0.6rem;
}

.text-container {
  text-align: left;
  font-size: small;
}

.container {
  margin-top: 40px;
  padding-top: 70px;
}

#main-container {
  background-color: #ffff;
  color: #575757;
  padding: 2rem 3rem;
}
</style>