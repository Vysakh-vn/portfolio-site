<template>
    <div class="d-flex justify-content-center" id="education">
        <h3 class="skills-heading mb-4">EDUCATION</h3>
    </div>
    <div class="d-flex justify-content-center">
        <div class="education-container col-10 rounded shadow">
            <div class="text-container">
                <ul class="education-list">
                    <li class="education-row">
                        <div class="marker">
                        <div class="dot"></div>
                        <div class="line"></div>
                        </div>
                        <div class="education-text">
                            <p class="year">2018 - 2022</p>                            
                            <p class="education-institute">College of Engineering, Muttathara</p>
                            <h5>Bachelor of Technology</h5>
                            <p><b>CGPA : </b>7.5</p>
                            <P><b>Department : </b> Electronics and Communications</P>
                            <br>
                            <br>
                        </div>
                    </li>
                    <li class="education-row">
                        <div class="marker">
                        <div class="dot"></div>
                        <div class="line"></div>
                        </div>
                        <div class="education-text">
                            <p class="year">2016 - 2018</p>                            
                            <p class="education-institute">St. Joseph's Higher Secondary Boys, Trivandrum</p>
                            <h5 class="">Higher Secondary Education</h5>
                            <p><b>Percentage : </b>85%</p>
                            <P><b>Group : </b>Computer Science</P><br>
                        </div>
                    </li>
                    <li class="education-row">
                        <div class="marker">
                        <div class="dot"></div>
                        <div class="line"></div>
                        </div>
                        <div class="education-text">
                            <p class="year">2004 - 2016</p>                            
                            <p class="education-institute">Lourdes Mount Higher Secondary School</p>
                            <h5>High School Education</h5>
                            <p><b>Percentage : </b>99%</p>
                            <P><b>Department : </b>Science</P>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>
<style>
.year {
    color: #c1c1c2;
}

.education-institute {
    margin-bottom: 0.7rem;
}

.education-list {
    margin: 0;
    padding: 0;
}

ul p {
    margin-bottom: 0;
}

.education-container {
    background-color: white;
    color: #858585;
    padding: 2rem 3rem;
}

h5 {
    font-weight: 600 !important;
}

.text-container {
    text-align: left;
    font-size: small;
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

ul {
    list-style-type: none;
}

.education-row {
    display: flex;
}

.education-text {
    margin-left: 10px;
    display: inline-block;
}

</style>