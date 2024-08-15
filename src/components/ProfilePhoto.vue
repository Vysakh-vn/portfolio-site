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
    height: 70px;
}

#profile-photo {
    position: absolute;
    bottom: 0;
    max-width: 190px;
    max-height: 190px;
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

@media (max-width: 600px) {
    #profile-photo {
        width: 150px;
        height: 150px;
    }
}

</style>