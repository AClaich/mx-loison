<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex d-md-none">
                <h1 class="mb-5">Contact</h1>
            </div>
            <div class="col-12 col-lg-6">
                <div id="carouselExampleFade" class="carousel slide carousel-fade" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="../assets/img/Photo Margaux Danse-099.jpg" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="../assets/img/Photo Margaux Danse-141.jpg" class="d-block w-100" alt="...">
                        </div>
                        <!-- <div class="carousel-item">
                            <img src="..." class="d-block w-100" alt="...">
                        </div> -->
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
            <div class="col-12 col-lg-6">
                <h1 class="mb-5 d-md-flex d-none">Contact</h1>
                <!-- <div class="row">
                    <textarea class="form-control col-6" aria-label="With textarea"></textarea>
                    <button type="button" class="btn btn-primary" @click="onClick">Envoyer</button>
                </div> -->

                <div class="row mb-5">
                    <h3 class="col-12 col-lg-6">Margaux Loison</h3>
                    <ul class="col-12 col-lg-6">
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
                <div class="row mb-5">
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
                        <li>
                            <a class="col-6 text-center" role="button" style="width: fit-content" href="tel:0769551526"
                                target=”_blank”>
                                <i class="bi bi-telephone"></i> 07.69.55.15.26
                            </a>
                        </li>
                    </ul>
                </div>

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