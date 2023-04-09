<template>
  <div class="selling-points flex justify-center">
    <section class="access">
      <div v-html="getSvg('access')"></div>
      <h2>Access your files, anywhere</h2>
      <p>The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.</p>
    </section>
    <section class="security">
      <div v-html="getSvg('security')"></div>
      <h2>Security you can trust</h2>
      <p>2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.</p>
    </section>
    <section class="collaboration">
      <div v-html="getSvg('collaboration')"></div>
      <h2>Real-time collaboration</h2>
      <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.</p>
    </section>
    <section class="anyfile">
      <div v-html="getSvg('anyfile')"></div>
      <h2>Store any type of file</h2>
      <p>Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.</p>
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