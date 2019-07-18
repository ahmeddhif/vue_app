<template>
  <div id="app">
    <div class="container">
      <Titi />
      <Toto/>
    </div>
  </div>
</template>

<script>
import Toto from "./components/Toto.vue";
import Titi from "./components/Titi.vue";

export default {
  name: "app",
  components: {
    Toto,
    Titi
  }
};
</script>

<style>

</style>
