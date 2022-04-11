<template>
  <div id="app">
    <MyTitle />
    <MainJumbo />
  </div>
</template>

<script>
import MyTitle from "./components/MyTitle.vue";
import MainJumbo from "./components/MainJumbo.vue";

export default {
  name: "App",
  components: {
    MyTitle,
    MainJumbo,
  },
};
</script>

<style>
html{
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

body{
  background: rgb(14, 14, 14);
}
</style>