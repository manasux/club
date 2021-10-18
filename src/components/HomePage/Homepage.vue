<template>
  <div class="homepage">
    <Taskbar />
  </div>
</template>

<script>
import Taskbar from "../TaskBar/Taskbar.vue";

export default {
  components: {
    Taskbar,
  },
};
</script>

<style>
@import "./homepage.css";
</style>