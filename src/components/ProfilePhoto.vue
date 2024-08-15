<template>
    <div class="profile-container d-flex justify-content-center">
        <div id="profile-photo">
            <img :src="require('@/assets/vysakh.jpeg')" alt="Profile Photo">
        </div>
    </div>
</template>
<style>

.profile-container {
    position: relative;
    height: 5vw;
    max-height: 80px;
}

#profile-photo {
    position: absolute;
    bottom: 0;
    max-width: 150px;
    max-height: 150px;
    min-height: 100px;
    min-width: 100px;
    background-color: #b3b3b3;
    border-radius: 50%;
    z-index: 9999;
    overflow: hidden;
    border: 5px solid #A6ADF0;
}

#profile-photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>