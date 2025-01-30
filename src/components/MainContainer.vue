<template>

    <div class="container">

    <div class="d-flex justify-content-center">
    <div id="main-container" class="col-lg-10 col-md-10 col-10 rounded shadow">

      <ProfilePhoto/>

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
        
      <p>Experienced Java developer skilled in designing, developing, and deploying robust software solutions. Proficient in
      Java and Spring Boot, with expertise in launching 20+ RESTful APIs, optimizing code quality, and enhancing system
      stability.</p>
      <button id="btn">Get in touch</button>

      <SocialMedia/>
    </div>
    </div>
  </div>

<SkillsComponent/>

</div>

</template>
<script>
import ProfilePhoto from './ProfilePhoto.vue'
import SocialMedia from './SocialMedia.vue'
import SkillsComponent from './SkillsComponent.vue'

export default {
  components: {
    ProfilePhoto, SocialMedia, SkillsComponent
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
  padding: 70px;
}

#main-container {
  background-color: #ffff;
  color: #575757;
  padding: 2rem 3rem;
}

</style>