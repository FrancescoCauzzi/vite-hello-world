<script>
export default {
  data() {
    return {
      message: "La mia prima app con Vite & Vue",
    };
  },
};
</script>

<template>
  <div class="__my-div">
    <h1>
      {{ message }}
    </h1>
    <img src="../assets/logo.svg" alt="" />
  </div>
</template>

<style scoped>
h1 {
  color: rgb(0, 255, 42);
  font-weight: bolder;
  text-align: center;
  margin-bottom: 30px;
}

img {
  width: 45px;
  height: 45px;
}
.__my-div {
  display: flex;
  justify-content: center;
}
</style>
