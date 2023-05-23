<template>
    <nav class="navbar navbar-expand-lg rounded m-auto blur">
        <div class="container ps-3 px-lg-5">
            <a class="navbar-brand" href="/"><b class="title">Margaux Loison</b></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02"
                aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
                <ul class="navbar-nav mx-0 mx-lg-auto">
                    <li class="nav-item mx-0 ms-lg-auto me-lg-5">
                        <a class="nav-link" href="/danse"><b>Danse</b>
                        </a>
                    </li>
                    <li class="nav-item mx-0 mx-lg-5">
                        <a class="nav-link" href="/about"><b>À propos</b>
                        </a>
                    </li>
                    <li class="nav-item mx-0 mx-lg-5">
                        <a class="nav-link" href="/diplome"><b>Diplômes & certificats</b></a>
                    </li>
                    <!-- <li class="nav-item">
                        <a class="nav-link" href="">Où me trouver</a>
                    </li> -->
                    <li class="nav-item mx-0 ms-lg-5 me-lg-auto">
                        <a class="nav-link" href="/contact"><b>Contact</b>
                        </a>
                    </li>
                </ul>
                <div class="row">
                    <a class="col-6 text-center align-middle" role="button" style="width: fit-content" href="">
                        <i class="bi bi-instagram" id="insta" aria-hidden="true"></i>
                    </a>
                    <a class="col-6 text-center" role="button" style="width: fit-content" href="">
                        <i class="bi bi-facebook" id="facebook" aria-hidden="true"></i>
                    </a>
                    <a class="col-6 text-danger text-center" role="button" style="width: fit-content" href="">
                        <i class="bi bi-youtube" id="youtube" aria-hidden="true"></i>
                    </a>
                </div>
            </div>
        </div>
    </nav>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Poiret+One');

nav{
    font-family: 'Poiret One', sans-serif;
    font-size: 20px;
}

.title{
    font-size: 22px;
}

#youtube {
    font-size: 22px;
}

#facebook {
    color: #3b5998;
    font-size: 22px;
}

#insta {
    margin-top: auto;
    margin-bottom: auto;
    display: inline-block;
    width: 22px;
    height: 22px;
    border-radius: 6px;
    color: #fff;
    font-size: 14px;
    background: #d6249f;
    background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%, #d6249f 60%, #285AEB 90%);
    /* box-shadow: 0px 3px 10px rgba(0, 0, 0, .25); */
}
</style>