<template>
    <div class="container">
        <div class="row">
            <div class="col-12 col-lg-6">
                <h1 class="text-center mb-5 mb-lg-2">Contact</h1>
            </div>
            <div class="col-12 col-lg-6">
            </div>
        </div>
        <div class="row mb-5">
            <div class="col-12 col-lg-6 text-center px-0 px-lg-5">
                <div class="mb-5 px-0 px-lg-5 h-50 d-flex align-items-center">
                    <ul class="list-contact">
                        <li class="mt-4">
                            <a class="col-6" role="button" style="width: fit-content"
                                href="mailto:margauxloisonpro@gmail.com" target=”_blank”>
                                <i class="bi bi-envelope" id="mail"></i> margauxloisonpro@gmail.com
                            </a>
                        </li>
                        <li class="mt-4">
                            <a class="col-6 text-center" role="button" style="width: fit-content"
                                href="https://www.instagram.com/margauxloison.pro/" target=”_blank”>
                                <i class="bi bi-instagram" id="insta" aria-hidden="true"></i> margauxloison.pro
                            </a>
                        </li>
                        <li class="mt-4">
                            <a class="col-6" role="button" style="width: fit-content"
                                href="https://www.facebook.com/profile.php?id=100093111573881" target=”_blank”>
                                <i class="bi bi-facebook" id="facebook" aria-hidden="true"></i> Margaux Loison Pro
                            </a>
                        </li>
                        <!-- <li class="mt-3">
                            <a class="col-6 text-center" role="button" style="width: fit-content" href="tel:0769551526"
                                target=”_blank”>
                                <i class="bi bi-telephone"></i> 07.69.55.15.26
                            </a>
                        </li> -->
                    </ul>
                </div>
                <div class="d-lg-block d-none">
                    <hr>
                    <h3 class="text-center ">Crédits</h3>
                    <div class="d-flex fs-6">
                        <div>Photographes : &nbsp;</div>
                        <div><a href="http://stephan-photographe.fr/" target=”_blank”> Stéphan
                                Gabrielli</a><br>
                            <a href="https://instagram.com/henriaubron?igshid=MzRlODBiNWFlZA==" target=”_blank”> Henri
                                Aubron</a>
                        </div>
                    </div>
                    <div class="d-flex fs-6">
                        <p>Développement : &nbsp;<a href="https://www.linkedin.com/in/alexis-claich-5897a7b9/"
                                target=”_blank”>Alexis Claich</a></p>
                    </div>
                </div>
            </div>
            <div class="col-12 col-lg-6 d-flex justify-content-center align-items-center">
                <div id="carouselExampleFade" class="carousel slide w-carousel" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="3000">
                            <img src="../assets/img//carousel-2/PhotoCarousel1.jpg" class="d-block w-100"
                                alt="...">
                        </div>
                        <div class="carousel-item" data-bs-interval="3000">
                            <img src="../assets/img/carousel-2/PhotoCarousel2.jpg" class="d-block w-100"
                                alt="...">
                        </div>
                        <div class="carousel-item" data-bs-interval="3000">
                            <img src="../assets/img/carousel-2/PhotoCarousel3.jpg" class="d-block w-100"
                                alt="...">
                        </div>
                        <div class="carousel-item" data-bs-interval="3000">
                            <img src="../assets/img/carousel-2/PhotoCarousel4.jpg" class="d-block w-100"
                                alt="...">
                        </div>
                        <div class="carousel-item" data-bs-interval="3000">
                            <img src="../assets/img/carousel-2/PhotoCarousel5.jpg" class="d-block w-100"
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
        <div class="d-block d-lg-none mb-3">
            <hr>
            <h3 class="text-center">Crédits</h3>
            <div class="d-flex fs-6">
                <div>Photographes : &nbsp;</div>
                <div><a href="http://stephan-photographe.fr/" target=”_blank”> Stéphan
                        Gabrielli</a><br>
                    <a href="https://instagram.com/henriaubron?igshid=MzRlODBiNWFlZA==" target=”_blank”> Henri
                        Aubron</a>
                </div>
            </div>
            <div class="d-flex fs-6">
                <p>Développement : <a href="https://www.linkedin.com/in/alexis-claich-5897a7b9/" target=”_blank”>Alexis
                        Claich</a></p>
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