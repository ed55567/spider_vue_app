<template>
  <div class="home">
    <h1>{{ message }}</h1>
  </div>
</template>

<style>
body {
  background-image: url("../assets/images/spiderman_wallpaper.jpg");
}
</style>

<script>
export default {
  data: function () {
    return {
      message: "Welcome to the Spider Verse!",
    };
  },
  created: function () {},
  methods: {},
};
</script>

