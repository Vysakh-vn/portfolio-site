<template>
    <div class="d-flex justify-content-center">
        <h3 class="skills-heading mb-4">SKILLS</h3>
    </div>
    <div class="d-flex justify-content-center">
        <div id="skills-container" class="col-lg-10 col-md-10 col-10">
            
            <div class="row1">
            <div class="java rounded shadow">
                <img :src="require('@/assets/github.svg')">
            </div>
            <div class="rounded shadow"></div>
            </div>

        </div>
    </div>
</template>
<style>

.row1 div {
    background-color: white;
    padding: 1rem;
}

.java {
    width: 2rem;
    height: 2rem;
}

.skills-heading {
    font-weight: 600;
    color: #818181;
    margin-top: 7rem;
}

#skills-container {
  color: #575757;
  padding: 2rem 3rem;
}

.row1 {
  display: flex;
  gap: 2rem;
  justify-content: center;
  flex-wrap: wrap;
}

</style>