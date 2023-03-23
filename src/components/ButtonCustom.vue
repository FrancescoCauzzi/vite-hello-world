<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
};
</script>

<template>
  <button @click="count++">
    You clicked me <span>{{ count }}</span> times.
  </button>
</template>

<style>
button {
  height: 40px;
  border-radius: 25px;
  padding: 5px 5px 5px 5px;
  font-size: 1.3em;
  font-weight: bolder;
}
span {
  color: red;
  font-weight: bolder;
  background-color: cadetblue;
  padding: 5px 5px 5px 5px;
  border-radius: 25px;
}
</style>
