<template>
    <div class="outercontainer d-flex">
        <div class="container d-flex flex-column justify-content-start">
            <h5>Hi my name is</h5>
            <h4 class="ms-5">Paul Christian Villa Sadio</h4>
            <h5 class="mt-3">Birthday: December 25, 1999</h5>
            <h5 class="mt-3">Bachelor's Degree: </h5>
            <h5 class="ms-5">Bachelor in Engineering Technology</h5>
            <h5><span class="ms-5">Major in Computer Engineering Technology</span></h5>
            <h5 class="mt-3">About Me:</h5>
            <h5 class="ms-5">I’m a front-end web developer in training and i 
aspire to be a full stack developer in the future. I enjoy 
fixing problems, learning new things and help others. I 
work hard and strive to be better, i take criticism as a 
guide for what i should improve on my self.</h5>
        </div>
        <div class="container d-flex justify-content-end">
            <img src="@/assets/Resume.jpg" alt="Photo">
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.outercontainer {
    border: solid 2px #683E80;
    margin: 5rem;
    border-radius: 25px;
    padding: 2rem;
    
}
.continer {
    height: 80%;
}
img{
    height: 25rem;
}
h6, h5, h4 {
    color: #C6BECC;
}
h4{
    font-weight: 600;
}
</style>