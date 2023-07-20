<template>
    <section id="banner">
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img class="d-block w-100" src="img/header-1.jpg" alt="Slide 1">
                    <div class="carousel-caption d-none d-md-block">
                        <h1>Bem-vindo à Barbearia</h1>
                        <p>Os melhores cortes de cabelo e barba para você</p>
                        <a href="#contato" class="btn btn-primary">Agende seu horário</a>
                    </div>
                </div>
                <div class="carousel-item">
                    <img class="d-block w-100" src="img/header-6.jpg" alt="Slide 2">
                    <div class="carousel-caption d-none d-md-block">
                        <h1>Bem-vindo à Barbearia</h1>
                        <p>Os melhores cortes de cabelo e barba para você</p>
                        <a href="#contato" class="btn btn-primary">Agende seu horário</a>
                    </div>
                </div>
                <div class="carousel-item">
                    <img class="d-block w-100" src="img/header-1.jpg" alt="Slide 3">
                    <div class="carousel-caption d-none d-md-block">
                        <h1>Bem-vindo à Barbearia</h1>
                        <p>Os melhores cortes de cabelo e barba para você</p>
                        <a href="#contato" class="btn btn-primary">Agende seu horário</a>
                    </div>
                </div>
            </div>
            <!--
            <a  class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Anterior</span>
            </a>
            <a  class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Próximo</span>
            </a>
            -->
        </div>
    </section>
</template>

<script>
export default {
    name: "Banner"
}

</script>

<style scoped>

#banner {
  
   /* background-image: url('img/header-1.jpg'); */
    background-size: cover;
    color: #fff;
    margin-top: -296px;

  /*  position: relative;
    overflow: hidden;
    margin-top: -296px; */ /* Ajusta o espaçamento negativo para sobrepor o header */
}
    
#banner .carousel {
    position: relative;
    top: 0;
    left: 0;
    width: 100%;
    height: auto;
    z-index: -1;
}

#banner .carousel .carousel-item {
    height: auto;
}

#banner .carousel .carousel-inner {
    width: 100%;
    height: auto;
}

#banner .carousel .carousel-item img {
    object-fit: cover; /* Faz a imagem ocupar todo o espaço disponível no slider */
    width: 100%;
    height: 100%;
}

</style>