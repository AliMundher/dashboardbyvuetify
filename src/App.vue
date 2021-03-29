<template>
  <v-app class="grey lighten-3">
    <Navbar />
    <v-content fluid class="mx-4 mt-3">
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
export default {
  name: "App",
  components: {
    Navbar,
  },
  data: () => ({
    //
  }),
};
</script>
