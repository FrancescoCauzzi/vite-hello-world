<script>
import ButtonCustom from "./components/ButtonCustom.vue";
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  components: {
    ButtonCustom,
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <header>
    <AppTitle />
    <AppHero />
  </header>
  <main>
    <ButtonCustom />
  </main>
  <footer></footer>
</template>

<style></style>
