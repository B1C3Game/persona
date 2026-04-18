<script setup>
import PersonaReveal from './components/PersonaReveal.vue'
import persona from './alex-rivera.persona.json'
</script>

<template>
  <div>
    <PersonaReveal :persona="persona" />
    <div style="margin-top:2em; color:#888; font-size:0.95em; text-align:center;">
      <em>Note: This demo has only been manually tested by viewing in the browser. No automated tests have been implemented yet.</em>
    </div>
  </div>
</template>
