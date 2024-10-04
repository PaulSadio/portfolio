<template>
    <div id="skills" class="mx-5 outercontainer">
        <div class="ms-2 flex-grow-1" style="height: 20%;">
            <h1>Skills</h1>
            <div class="d-flex justify-content-center hLine" >
                <div class="mt-2" style="width: 95%;height: .1rem; background-color:#683E80; transform: translateY(-20px);"></div>
            </div>
        </div>
        <div class=" container d-flex justify-content-between p-3">
            <div class="text-center">
                <img src="../assets/bootstrap-logo.png" alt="Bootstrap">
                <p>1 out of 5</p>
            </div>
            <div class="text-center">
                <img src="../assets/CSS3_logo.svg.png" alt="CSS">
                <p>1 out of 5</p>
            </div>
            <div class="text-center">
                <img src="../assets/html5.png" alt="HTML">
                <p>1 out of 5</p>
            </div>
            <div class="text-center">
                <img src="../assets/javascript.png" alt="JS">
                <p>1 out of 5</p>
            </div>
            <div class="text-center">
                <img src="../assets/laravel.png" alt="Laravel">
                <p>1 out of 5</p>
            </div>
            <div class="text-center">
                <img src="../assets/php.png" alt="PHP">
                <p>1 out of 5</p>
            </div>
            <div class="text-center">
                <img src="../assets/vue.png" alt="Vue.js">
                <p>1 out of 5</p>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
h1,p{
    color: #683E80;
}
.outercontainer{
    padding: 2rem;
    height: 100vh;
}
img {
    height: 5rem;
    width: 5rem;
}
p {
    margin-top: .5rem;
}
</style>