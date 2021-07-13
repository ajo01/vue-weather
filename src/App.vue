<template>
  <div id="app">
  <main>
    <div class="search-box">
      <input type="text" name="" id="" class="search-bar" placeholder="Search">
    </div>
  </main>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      api_key: "92bb94446ae83a4d0612357549eb65c9",
    };
  },
};
</script>

<style>
  *{
    margin:0;
    padding:0;
    box-sizing: border-box;
  }

  body {
    font-family:'montserrat',sans-serif;
  }

  #app{
    background-image: url('./assets/cold-bg.jpeg');
  }
</style>
