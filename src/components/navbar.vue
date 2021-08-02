<template>
  <section class="section section_1">
  <div class="container">
    <nav class="navbar navbar-expand-lg">
      <div class="col-md-4">
        <a class="navbar-brand d-flex align-items-center" href="#">
          <img src="../assets/logo.svg" width="42" height="42" class="pr-2">
          <img src="../assets/Tourist39.png" height="20">
        </a>
      </div>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="col-md-4">
      <div class="collapse navbar-collapse d-flex justify-content-center" id="navbarSupportedContent">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link" active-class="active" to="/" exact>Клиентам<span class="sr-only">(current)</span></router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/partners" active-class="active">Партнерам</router-link>
          </li>
        </ul>
      </div>
      </div>
      <div class="col-md-4 text-right text_body">
        <img src="../assets/Phone.svg" class="pb-2 pr-2">
        <a href="tel:7-812-309-93-470" type="tel" class="primary-text">+7(812) 309-93-47</a>
      </div>
    </nav>
  </div>
  </section>
</template>
<script lang="js">
export default {
  name: 'Navbar'
}
</script>
<style src="../styles/main.sass" lang="sass">
a.primary-text
  color: $primary !important
</style>
