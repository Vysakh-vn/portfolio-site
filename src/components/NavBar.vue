<template>
<nav id="main-navbar" class="navbar navbar-expand-lg">
  <a class="navbar-brand ms-5" href="#"><b>Vysakh V N</b></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a @click="scrollToSection('about')" class="nav-link">ABOUT</a>
      </li>
      <li class="nav-item">
        <a @click="scrollToSection('skills')" class="nav-link">SKILLS</a>
      </li>
      <li class="nav-item">
        <a @click="scrollToSection('experience')" class="nav-link">EXPERIENCE</a>
      </li>
      <li class="nav-item">
        <a @click="scrollToSection('education')" class="nav-link">EDUCATION</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">PROJECTS</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">CONTACT</a>
      </li>
    </ul>
  </div>
</nav>
</template>

<script setup>

function scrollToSection(sectionId) {
  const section = document.getElementById(sectionId);
  if(section) {
    section.scrollIntoView({ behavior: "smooth" });
  }
}

</script>

<style>
#main-navbar {
background-color: #ffff;
font-size: 12px;
}

#main-navbar .navbar-nav .nav-item {
  margin-left: 2rem;
}

</style>