<script>
export default {
  data() {
    return {};
  },
};
</script>

<template>
  <div class="__jumbo">
    <div class="__image">
      <img
        src="../assets/images/spiderman.jpg"
        alt="Cannot retrieve the image"
        srcset=""
      />
    </div>
    <div class="__subtitle">
      <h2>Use Vue like Spiderman uses his superpowers!!</h2>
      <a href="https://vuejs.org/guide/introduction.html"
        >Click Here to get started with Vue and Vite</a
      >
    </div>
  </div>
</template>

<style>
.__image {
  width: 50%;
}

img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.__subtitle {
  width: 50%;
  text-align: center;
}

.__jumbo {
  display: flex;
  gap: 10px;
  padding: 20px;

  align-items: center;
  justify-content: center;
}

a {
  color: white;
  font-size: 1.2em;
}
</style>
