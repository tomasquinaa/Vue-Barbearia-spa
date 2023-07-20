<template>
    <Banner />
    <div class="main-container">
      <section id="sobre">
          <div class="container">
              <div class="row">
                  <div class="col-md-12">
                    <h2>Sobre</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin aliquet tellus quis velit pretium, a hendrerit nunc fermentum.</p>
                  </div>
              </div>
          </div>
      </section>
    </div>
</template>

<script>
import Banner from "../components/Banner.vue"

export default {
  name: "About",
  components: {
    Banner 
  }
}
</script>

<style>
#sobre {
    background-color: #f2f2f2;
}

</style>

