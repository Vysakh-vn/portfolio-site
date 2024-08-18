<template>
    <div class="d-flex justify-content-center">
        <h3 class="skills-heading mb-4">SKILLS</h3>
    </div>
    <div class="d-flex justify-content-center">
        
        <div id="skills-container" class="col-lg-10 col-md-10 col-10 p-0">
            
            <div class="firstrow">
            <div class="java col-lg-2 col-md-4 col-5 shadow rounded">
                <img :src="require('@/assets/java.svg')">
            </div>
            <div class="springboot col-lg-2 col-md-4 col-5 rounded shadow">
                <img :src="require('@/assets/springboot.svg')">
            </div>
            <div class="springboot col-lg-2 col-md-4 col-5 rounded shadow">
                <img :src="require('@/assets/rest-api-icon.svg')">
            </div>
            <div class="springboot col-lg-2 col-md-4 col-5  rounded shadow">
                <img :src="require('@/assets/mysql-official.svg')">
            </div>
            <div class="springboot col-lg-2 col-md-4 col-5 rounded shadow">
                <img :src="require('@/assets/html-1.svg')">
            </div>
            </div>

            <!-- second row -->

            <!-- <div class="firstrow">
            <div class="java col-lg-2 col-md-4 col-6 shadow rounded">
                <img :src="require('@/assets/java.svg')">
            </div>
            <div class="springboot col-lg-2 col-md-4 col-6 rounded shadow">
                <img :src="require('@/assets/springboot.svg')">
            </div>
            <div class="springboot col-lg-2 col-md-4 col-6 rounded shadow">
                <img :src="require('@/assets/rest-api-icon.svg')">
            </div>
            <div class="springboot col-lg-2 col-md-4 col-6 rounded shadow">
                <img :src="require('@/assets/mysql-official.svg')">
            </div>
            <div class="springboot col-lg-2 col-md-4 col-6 rounded shadow">
                <img :src="require('@/assets/html-1.svg')">
            </div>
            </div> -->

        </div>
    </div>
</template>
<style>

.firstrow {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
.firstrow div {
    background-color: white;
    padding: 0.5rem;
}

.firstrow img {
    width: 70px;
}

@media (max-width: 600px) {
    .firstrow img {
    width: 50px;
}
/* .firstrow div {
    margin: 1rem;
} */
}

.skills-heading {
    font-weight: 600;
    color: #818181;
    margin-top: 7rem;
}

#skills-container {
  color: #575757;
}

</style>