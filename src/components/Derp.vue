<template>
  <div>
    <p>Derp derp derp</p>
    <p>
      Here's a random button
      <button type="button" @click="derp">Click me!</button>
    </p>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class Derp extends Vue {
  derp() {
    alert("I derped");
  }
}
</script>
