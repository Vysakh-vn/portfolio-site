<template>
    <div class="project-component-main rounded shadow">
        <div class="heading">
            <img :src="require('@/assets/github.svg')" alt="Github logo">
            <p><b>Desing Patterns</b></p>
        </div>
        <div class="tags">
            <div>#Java</div>
            <div>#OOPs</div>
        </div>
        <div class="description">
            <p>Implementation of design patterns in Java.</p>
        </div>
    </div>
</template>
<style scoped>

.project-component-main {
    padding: 40px 30px;
    background-color: white;
}

.project-component-main img {
    width: 15px;
    margin-right:  5px;
    opacity: 0.5;
}

.heading {
    display: flex;
    align-items: center;
}

.heading p {
    margin: 0;
    color: #858585;
    font-size: 0.9rem;
}

.tags {
    display: flex;
    gap: 10px;
}

.tags div {
    border-radius: 50px;
    padding: 1px 10px;
    background-color: #e1e3e7;
    color: #858585;
    font-size: 0.7rem;
    margin-top: 10px;
}

.description p {
    color: #858585;
    font-size: 0.9rem;
}

</style>