<template>
    <div class="nav d-flex flex-row align-items-center justify-content-between px-5" id="home">
        <div >
            <img src="@/assets/logo.jpg" alt="logo" style="height: 4rem;">
        </div>
        <div>
            <a class="ms-4" href="#home">Home</a>
            <a class="ms-4" href="#education">Education</a>
            <a class="ms-4" href="#portfolio">Portfolio</a>
            <a class="ms-4" href="#skills">Skills</a>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.nav {
    background-color: #0B0B0B;
    height: 5rem;
}
a {
    text-decoration: none;
    color: #683E80;
    font-size: 1.3rem;
}
</style>