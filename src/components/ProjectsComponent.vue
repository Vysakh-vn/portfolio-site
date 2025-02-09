<template>
    <div class="project-component-main rounded shadow" @click="openLink">
        <div class="heading">
            <img :src="require('@/assets/github.svg')" alt="Github logo">
            <p><b>{{ title }}</b></p>
        </div>
        <div class="tags">
            <div v-for="(tags, index) in tags" :key="index">#{{ tags }}</div>
            <!-- <div>#Java</div> -->
            <!-- <div>#OOPs</div> -->
        </div>
        <div class="description">
            <!-- <p>Java implementations of various design patterns. Each pattern includes examples and use cases for
                easy understanding.</p> -->
            <p>{{ description }}</p>
        </div>
    </div>

</template>
<script>
export default {
    props: {
        title: String,
        url: String,
        tags: Array,
        description: String
    },
    methods: {
        openLink() {
            window.location.href = this.url;
        }
    }
}
</script>
<style scoped>
.project-component-main {
    cursor: pointer;
    padding: 25px 30px;
    background-color: white;
    flex: 1;
    transition: transform 0.3s ease-in-out;
}

.project-component-main:hover {
    transform: scale(1.02);
}

.project-component-main img {
    width: 15px;
    margin-right: 5px;
    opacity: 0.5;
}

.heading {
    display: flex;
    align-items: center;
    padding: 5px;
}

.heading p {
    margin: 0;
    color: #6f7882;
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
    color: #a1a1a1;
    font-size: 0.7rem;
    margin-top: 10px;
}

.description p {
    color: #a1a1a1;
    font-size: 0.8rem;
    margin-top: 10px;
    text-align: left;
}
</style>