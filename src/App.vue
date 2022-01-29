<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  <h1 class="name">张三</h1>
</template>

<script lang="ts">
import HelloWorld from "/@/components/HelloWorld.vue";
import "./assets/app.css";

const sport: string = "篮球";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  mounted() {
    console.log(sport);
  },
};
</script>

<style lang="scss">
.name {
  font-size: 16px;
}
</style>
