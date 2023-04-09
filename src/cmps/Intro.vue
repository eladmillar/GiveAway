<template>
  <div class="intro flex column align-center">
    <img src="../assets/images/illustration-intro.png" alt />
    <h1>All your files in one secure location, accessible anywhere.</h1>
    <h3>Fylo stores all your most important files in one secure location. Access them wherever you need, share and collaborate with friends family, and co-workers.</h3>
    <button>Get Started</button>
    <div class="bg-desktop" v-html="getSvg('bgdesktop')"></div>
  </div>
</template>

<script>
import { svgService } from "../services/svg.service.js";

export default {
  methods: {
    getSvg(iconName) {
      return svgService.getSvg(iconName);
    }
  }
};
</script>
