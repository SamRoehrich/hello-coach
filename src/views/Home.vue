<template>
  <div class="home">
    <Header />
    <Dash />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Dash from "@/components/Dash.vue";

export default {
  name: "Home",
  components: {
    Header,
    Dash,
  },
};
</script>
