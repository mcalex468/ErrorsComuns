<script setup>
import AboutComponent from './components/AboutComponent.vue';
import Desti from './components/Desti.vue';
import HelloWorld from './components/HelloWorld.vue'
import KeyForSample from './components/KeyForSample.vue';
import NameSurname from './components/NameSurname.vue';
import PrecioProducto from './components/PrecioProducto.vue';
import RouterApp from './components/RouterApp.vue';
import TheWelcome from './components/TheWelcome.vue'
import WatchArrayExample from './components/WatchArrayExample.vue';
import ViewAbout from './views/ViewAbout.vue';
</script>

<template>
 

  <main>
  <KeyForSample/>
  <WatchArrayExample/>
  <AboutComponent/>
  <NameSurname/>
  <PrecioProducto/>
  <RouterApp/>
  <Desti/>
  </main>
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
