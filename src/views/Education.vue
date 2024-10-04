<template>
    <div id="education" class="mx-5 outercontainer ">
        <div class="ms-2 mt-4">
            <h1>Education</h1>
            <div class="d-flex justify-content-center hLine" >
                <div class="mt-2" style="width: 95%;height: .1rem; background-color:#683E80; transform: translateY(-20px);"></div>
            </div>
        </div>

        <div class="d-flex flex-row justify-content-between mt-5 text-center">
            <div class="d-flex flex-column school ms-4 align-items-center">
                <div>
                    <img src="@/assets/SSES.jpg" alt="School Logo">
                </div>
                <div class="mt-4">
                    <div class="d-flex flex-column">
                        <h4>Primary School:</h4>
                        <h5>Silay South Elementary School</h5>
                    </div>
                    <div class="d-flex flex-column">
                        <h5>School Year: 2006 - 2012</h5>
                    </div>
                </div>
            </div>

            <div class="d-flex flex-column school ms-4 align-items-center">
                <div>
                    <img src="@/assets/SJS-LS.jpg" alt="School Logo">
                </div>
                <div class="mt-4">
                    <div class="d-flex flex-column">
                        <h4>Secondary School:</h4>
                        <h5>St. Joseph School La Salle</h5>
                    </div>
                    <div class="d-flex flex-column">
                        <h5>School Year: 2012 - 2016</h5>
                    </div>
                </div>
            </div>

            <div class="d-flex flex-column school ms-4 align-items-center">
                <div>
                    <img src="@/assets/TUPV.png" alt="School Logo">
                </div>
                <div class="mt-4">
                    <div class="d-flex flex-column">
                        <h4>Senior High School & Tertiary School:</h4>
                        <h5>Technological University of the Philippines Visayas</h5>
                    </div>
                    <div class="d-flex flex-column">
                        <h5>School Year: 2016 - 2022</h5>
                    </div>
                </div>
            </div>
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
.school img{
    height: 15rem;
    border-radius: 50%;
}
h4, h5{
   color: #C6BECC;
}
.school{
    border: #683E80 2px solid;
    border-radius: 25px;
    padding: 1rem;
    width: 30%;
    margin-top: 2rem;
}
</style>