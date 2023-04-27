<template>
  <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" /> -->
  <SideBar />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld.vue";
import SideBar from "./components/SideBar.vue";

export default defineComponent({
  name: "App",
  components: {
    // HelloWorld,
    SideBar,
  },
});
</script>

<style>
@import "./assets/styles/normalize.css";
@import "./assets/styles/global.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: flex;
}

/* .v-collapse {
  transition: height var(--vc-auto-duration) cubic-bezier(0.33, 1, 0.68, 1);
} */
</style>
