<template>
  <div class="container">
    <div class="columns">
      <div class="column">
        <div class="main-text">
          <div class="tagline-cta">
            <h1>
              The ultimate website for all your motopart needs
            </h1>
            <a class="button main-button">
              <strong>Discover the store</strong>
            </a>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="center">
          <img src="~/static/dirtbike-home.jpg" alt="Dirt bike wheel" class="splashbanner-img">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo,
  }
}
</script>
