<template>
  <header class="flex space-between align-center">
    <div class="logo">
      <span v-html="getSvg('logo')"></span>
    </div>
    <div class="header-links flex">
      <a>Features</a>
      <a>Team</a>
      <a>Sign In</a>
    </div>
  </header>
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