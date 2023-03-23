<script>
import ButtonCustom from "./components/ButtonCustom.vue";
import AppTitle from "./components/AppTitle.vue";

export default {
  components: {
    ButtonCustom,
    AppTitle,
  },
};
</script>

<template>
  <header>
    <AppTitle />
  </header>
  <main>
    <ButtonCustom />
  </main>
  <footer></footer>
</template>

<style></style>
