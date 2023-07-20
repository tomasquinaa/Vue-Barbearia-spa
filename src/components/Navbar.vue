<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
           <!-- <img src="img/logo.png" alt="Logo da Barbearia" class="logo-image"> --> 
            <RouterLink class="navbar-brand" to="/"><img :src="logo" :alt="alt" class="logo-image"></RouterLink>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <RouterLink class="nav-link" to="/">Home</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link" to="/about">Sobre</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link" to="/servicos">Serviços</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link" to="/contatos">Contato</RouterLink>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: "Navbar",
    props: ["logo", "alt"]
}
</script>

<style scoped>
    .navbar-brand img {
        height: 50px;
        width: auto;
    }

</style>