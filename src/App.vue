<script>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
import Servico from './views/Servicos/Info.vue'

export default {
  components: {
    Navbar,
    Footer,
    Servico  
  },
  data() {
    return {
      logo_src: "img/logo.png",
      app_name: "Logo da Barbearia"
    }
  }
}

</script>

<template>  
    <header>
      <div class="wrapper">
         <Navbar :logo="logo_src" :alt="app_name" />
      </div>
    </header>

  <RouterView />

    <Footer/>
</template>

<style scoped>
  * {
    font-family: Helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  .main-container {
    margin: 50px;
    min-height: 400px;
  }

</style>
