<template>
    <div>
        <!-- Menu -->
    <nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-dark ">
        <a class="navbar-brand " href="# ">
            <img src="public/images/Logo-misiontic.jpg" width="30 " height="30
            " class="d-inline-block align-top " alt=" " loading="lazy "> SEMANA-2-113
        </a>
        <div class="collapse navbar-collapse justify-content-end " id="navbarNav ">
            <ul class="navbar-nav ">
                <li class="nav-item active ">
                    <a class="nav-link " href="# ">Inicio <span class="sr-only ">(current)</span></a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link " href="# ">News</a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link " href="# ">Team</a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link " href="https://github.com/aaal79/semana-2-113.git"> Github </a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Banner -->
    <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="1" class=""></li>
            <li data-target="#carouselExampleCaptions" data-slide-to="2" class=""></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <svg class="bd-placeholder-img bd-placeholder-img-lg d-block w-100" width="800" height="400"
                    xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img"
                    aria-label="Placeholder: First slide">
                    <title>Placeholder</title>
                    <rect width="100%" height="100%" fill="#777"></rect><text x="50%" y="50%" fill="#555"
                        dy=".3em">First slide</text>
                </svg>
                <div class="carousel-caption d-none d-md-block">
                    <h5>First slide label</h5>
                    <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
                </div>
            </div>
            <div class="carousel-item">
                <svg class="bd-placeholder-img bd-placeholder-img-lg d-block w-100" width="800" height="400"
                    xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img"
                    aria-label="Placeholder: Second slide">
                    <title>Placeholder</title>
                    <rect width="100%" height="100%" fill="#666"></rect><text x="50%" y="50%" fill="#444"
                        dy=".3em">Second slide</text>
                </svg>
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
            </div>
            <div class="carousel-item">
                <svg class="bd-placeholder-img bd-placeholder-img-lg d-block w-100" width="800" height="400"
                    xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice" focusable="false" role="img"
                    aria-label="Placeholder: Third slide">
                    <title>Placeholder</title>
                    <rect width="100%" height="100%" fill="#555"></rect><text x="50%" y="50%" fill="#333"
                        dy=".3em">Third slide</text>
                </svg>
                <div class="carousel-caption d-none d-md-block">
                    <h5>Third slide label</h5>
                    <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
        

    </div>
</template>

<script>
    export default {
        name: "SectionMenu",
                }

</script>

<style scoped>

</style>
