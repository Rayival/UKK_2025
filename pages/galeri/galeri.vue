<template>
    <div class="container">
        <h4 class="mt-5">galeri <span class="text-dark"></span></h4>
        <div class="row mt-5 justify-content-center">
            <div class="col-5">
                <div class="card rounded-2">
                    <img src="~/assets/img/parkiran.jpg" class="card-img-top rounded-2" alt="img-artikel">
                    <div class="card-body p-2 mt-1">
                        <h6 class="text-center">Parkiran</h6>
                    </div>
                </div>
            </div>
            <div class="col-5">
                <div class="card rounded-2">
                    <img src="~/assets/img/masjid.jpg" class="card-img-top rounded-2" alt="img-artikel">
                    <div class="card-body p-2 mt-1">
                        <h6 class="text-center">masjid</h6>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-5 justify-content-center">
            <div class="col-5">
                <div class="card rounded-2">
                    <img src="~/assets/img/perpus.jpeg" class="card-img-top rounded-2" alt="img-artikel">
                    <div class="card-body p-2 mt-1">
                        <h6 class="text-center">Perpustakaan</h6>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
h4, h6 {
    font-family: "Poppins", serif;
}

h4 {
    margin-left: 95px;
}

.card {
    background-color: transparent;
    backdrop-filter: blur(20px);
    border: 2px solid #ffff;
}

</style>