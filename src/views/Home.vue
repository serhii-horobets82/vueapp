<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Default msg="Welcome" />
  </div>
</template>

<script>
import Default from "@/components/Default.vue";

export default {
  name: "home",
  components: {
    Default
  }
};
</script>
