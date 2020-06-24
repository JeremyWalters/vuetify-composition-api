<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  props: { msg: String },
  setup() {
    return {};
  }
});
</script>