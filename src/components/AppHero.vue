<script>
export default {
  data() {
    return {
      titolo: "MODERN ART",
      sottotitolo: "EXHIBITION",
      testo:
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque ac odio sapien. Nunc libero nulla, dapibus eu ex at, porta pellentesque ligula. ",
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
      <h2>{{ sottotitolo }}</h2>
      <p>{{ testo }}</p>
      <button class="btn">Discover more</button>
    </div>

    <img :src="immagine" />
  </div>
</template>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

button {
  font-weight: bold;
}
.main {
  background-color: #060a2d;
  display: flex;
}
.btn {
  background-color: #060a2d;
  border: 1px solid #c50b76;
  padding: 16px;
  border-radius: 10px;
  margin-top: 30px;
}

.titolo {
  text-align: left;
  padding: 50px;
}
h1 {
  margin-bottom: 20px;
  font-size: 70px;
}

h2 {
  margin-bottom: 50px;
  font-size: 50px;
}
</style>
