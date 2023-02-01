<script>
export default {
  data() {
    return {
      count: 0,
      message: "La mia prima app con Vite!",
    };
  },
};
</script>

<template>
  <h1 style="color: purple">{{ message }}</h1>
</template>

<style scoped>
button {
  font-weight: bold;
}

.purple {
  color: rgb(83, 2, 189);
}
</style>
