<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Vite, Vue 3x, & Bootstrap 5.2.3" />
    </div>
  </header>

  <main>
  </main>
  <div class="container" >
    <h3>Bootstrap image carousel</h3>
    <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://picsum.photos/id/211/600/300" class="d-block w-200" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://picsum.photos/id/212/600/300" class="d-block w-200" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://picsum.photos/id/213/600/300" class="d-block w-200" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://picsum.photos/id/214/600/300" class="d-block w-200" alt="...">
          </div>
          <div class="carousel-item">
            <img src="https://picsum.photos/id/215/600/300" class="d-block w-200" alt="...">
          </div>
      </div>
    </div>
   </div> 
   <br>
   <br>
   <br>
   <h4>project: junkboot</h4>
</template>


<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
