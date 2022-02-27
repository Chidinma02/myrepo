<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->

    <LandingPage></LandingPage>
    <FeAVue></FeAVue>
  </div>
</template>

<script>
// @ is an alias to /src

import LandingPage from "@/components/LandingPage.vue";
import FeAVue from "@/components/FeA.vue";

export default {
  name: "HomeView",
  components: {
    LandingPage,
    FeAVue,
  },
};
</script>
