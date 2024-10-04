<template>
    <div id="portfolio" class="mx-5 outercontainer">
        <div class="ms-2 flex-grow-1" style="height: 20%;">
            <h1>Portfolio</h1>
            <div class="d-flex justify-content-center hLine" >
                <div class="mt-2" style="width: 95%;height: .1rem; background-color:#683E80; transform: translateY(-20px);"></div>
            </div>
        </div>
        
            <div id="carouselExampleIndicators" class="carousel slide" style="height: 80%;">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner h-100">
                    <div class="carousel-item active h-100">
                        <img src="@/assets/imagePlacholder.png" class="d-block w-100" alt="Image">
                    </div>
                    <div class="carousel-item h-100">
                        <img src="@/assets/imagePlacholder.png" class="d-block w-100" alt="Image">
                    </div>
                    <div class="carousel-item h-100">
                        <img src="@/assets/imagePlacholder.png" class="d-block w-100" alt="Image">
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>
        </div>
   
</template>

<script setup>

</script>

<style scoped>
h1{
    color: #683E80;
}
.outercontainer{
    padding: 2rem;
    height: 100vh;
}
img{
   height: 100%;
   object-fit:contain;
}
p{
    color: #C6BECC;
}
</style>