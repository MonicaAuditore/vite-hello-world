<script>
export default {
  data() {
    return {
      titolo: "Titolo",
      sottotitolo: "lorem ipsum dolor sit amet",
      immagine:
        "https://p4.wallpaperbetter.com/wallpaper/123/100/61/abstract-graphic-design-vector-triangle-wallpaper-preview.jpg",
    };
  },
};
</script>

<template>
  <div class="main">
    <div class="titolo">
      <h1>{{ titolo }}</h1>
      <h4>{{ sottotitolo }}</h4>
    </div>

    <img :src="immagine" />
  </div>
</template>

<style scoped>
button {
  font-weight: bold;
}
.main {
  background-color: #060a2d;
  display: flex;
}

.titolo {
  text-align: left;
}
</style>
