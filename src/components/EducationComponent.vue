<template>
    <div class="d-flex justify-content-center" id="education">
        <h3 class="skills-heading mb-4">EDUCATION</h3>
    </div>
    <div class="d-flex justify-content-center">
        <div class="education-container col-10 rounded shadow">
            <div class="text-container">
                <ul>
                    <li>
                        <div class="line"></div>
                        <div class="dot"></div>
                        <div class="education-text">
                            <p> 2018 - 2022</p>
                            <p>B.tech (Electronics and Communications)</p>
                            <p>College of Engineering, Muttathara</p>
                        </div>
                    </li>
                </ul>

                <br><br>
                <p>2016 - 2018</p>
                <p>Higher Secondary</p>
                <p>St Joseph,s boys school, Trivandrum</p>
                <br><br>
                <p>2004 - 2016</p>
                <p>High School</p>
                <p>Lourdes Mount school, Trivandrum</p>
            </div>
        </div>
    </div>
</template>
<style>
.education-container {
    background-color: white;
    color: #575757;
    padding: 2rem 3rem;
}

.text-container {
    text-align: left;
    font-size: small;
}

.dot {
    display: inline-block;
    width: 12px;
    height: 12px;
    background-color: transparent;
    border-radius: 50%;
    border: 3px solid #A6ADF0;
}

.line {
    width: 1px;
    height: 100%;
    background-color: black;
    display: inline-block;
    
}

ul {
    list-style-type: none;
}

.education-text {
    margin-left: 10px;
    display: inline-block;
}

</style>