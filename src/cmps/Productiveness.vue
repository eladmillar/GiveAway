<template>
  <div class="productiveness flex justify-center align-center">
    <img src="../assets/images/illustration-stay-productive.png" alt />
    <section>
      <h1>
        Stay productive,
        wherever you are
      </h1>
      <p>Never let location be an issue when accessing your files. Fylo has you covered for all of your file storage needs.</p>
      <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.</p>
      <div>
        <a href>See how Fylo works</a>
        <span v-html="getSvg('arrowicon')"></span>
      </div>
    </section>
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