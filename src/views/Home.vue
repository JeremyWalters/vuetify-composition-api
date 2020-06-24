<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue typescript composition api app" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  name: "Home",
  components: {
    HelloWorld
  }
});
</script>
