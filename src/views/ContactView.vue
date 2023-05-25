<template>
    <div class="container">
        <div class="row">
            <div class="col-12 col-lg-6">
                <h1 class="text-center">Contact</h1>
                <div class="mb-5">
                    <ul class="">
                        <li>
                            <a class="col-6 text-center align-middle" role="button" style="width: fit-content"
                                href="mailto:margauxloisonpro@gmail.com" target=”_blank”>
                                <i class="bi bi-envelope"></i> margauxloisonpro@gmail.com
                            </a>
                        </li>
                        <li>
                            <a class="col-6 text-center align-middle" role="button" style="width: fit-content"
                                href="https://www.instagram.com/margauxloison.pro/" target=”_blank”>
                                <i class="bi bi-instagram" id="insta" aria-hidden="true"></i> margauxloison.pro
                            </a>
                        </li>
                        <li>
                            <a class="col-6 text-center" role="button" style="width: fit-content"
                                href="https://www.facebook.com/profile.php?id=100093111573881" target=”_blank”>
                                <i class="bi bi-facebook" id="facebook" aria-hidden="true"></i> Margaux Loison Pro
                            </a>
                        </li>
                        <li>
                            <a class="col-6 text-center" role="button" style="width: fit-content" href="tel:0769551526"
                                target=”_blank”>
                                <i class="bi bi-telephone"></i> 07.69.55.15.26
                            </a>
                        </li>
                    </ul>
                </div>

                <!-- <hr> -->
                <!-- <div class="row mb-5">
                    <div class="col-12 col-lg-6">
                        <h3>Stéphan Gabrielli</h3>
                        (Photographe)
                    </div>
                    <ul class="col-12 col-lg-6">
                        <li>
                            <a class="col-6 text-center align-middle" role="button" style="width: fit-content"
                                href="http://stephan-photographe.fr/" target=”_blank”>
                                <i class="bi bi-globe2"></i> stephan-photographe.fr
                            </a>
                        </li>
                        <li>
                            <a class="col-6 text-center align-middle" role="button" style="width: fit-content"
                                href="https://www.instagram.com/stephan_photographies_pro/" target=”_blank”>
                                <i class="bi bi-instagram" id="insta" aria-hidden="true"></i> stephan_photographies_pro
                            </a>
                        </li>
                        <li>
                            <a class="col-6 text-center" role="button" style="width: fit-content"
                                href="https://facebook.com/StephanPhotographies" target=”_blank”>
                                <i class="bi bi-facebook" id="facebook" aria-hidden="true"></i> Stephan Photographies
                            </a>
                        </li>
                    </ul>
                </div>
                <hr>
                <div class="row">
                    <div class="col-12 col-lg-6">
                        <h3>Alexis Claich</h3>
                        (développeur)
                    </div>
                    <ul class="col-12 col-lg-6">
                        <li>
                            <a class="col-6 text-center align-middle" role="button" style="width: fit-content"
                                href="https://www.linkedin.com/in/alexis-claich-5897a7b9/" target=”_blank”>
                                <i class="bi bi-linkedin" id="linkedin"></i> Alexis Claich
                            </a>
                        </li>
                    </ul>
                </div> -->
            </div>
            <div class="col-12 col-lg-6 d-flex justify-content-center align-items-center">
                <div id="carouselExampleFade" class="carousel slide w-carousel" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="3000">
                            <img src="../assets/img//carousel-2/Photo Margaux Danse-040.jpg" class="d-block w-100"
                                alt="...">
                        </div>
                        <div class="carousel-item" data-bs-interval="3000">
                            <img src="../assets/img/carousel-2/Photo Margaux Danse  NB-003 (1).jpg" class="d-block w-100"
                                alt="...">
                        </div>
                        <div class="carousel-item" data-bs-interval="3000">
                            <img src="../assets/img/carousel-2/Photo Margaux Danse -099.JPG" class="d-block w-100"
                                alt="...">
                        </div>
                        <div class="carousel-item" data-bs-interval="3000">
                            <img src="../assets/img/carousel-2/Photo Margaux Danse -016.jpg" class="d-block w-100"
                                alt="...">
                        </div>
                        <div class="carousel-item" data-bs-interval="3000">
                            <img src="../assets/img/carousel-2/Photo Margaux Danse -092.JPG" class="d-block w-100"
                                alt="...">
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Précédent</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Suivant</span>
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
ul {
    list-style-type: none
}

a {
    color: #212529
}

.w-carousel {
    width: 85%;
}

@media (min-width: 400px) {
    .w-carousel {
        width: 60%;
    }
}
</style>

<script>
export default {
    methods: {
        onClick() {
            console.log('test')
        }
    }
}
</script>