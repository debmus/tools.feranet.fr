<template>
  <v-app>
    <Navbar />

    <!--     <v-main class="ma-6">
      <router-view></router-view>
    </v-main> -->

    <go-top :size="50" bg-color="#2d88ed"></go-top>
    <!--     <Footer class="hidden-sm-and-down" />
    <Mobile class="hidden-md-and-up" /> -->
    <!-- <Footer /> -->
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
/* import Footer from "./components/Footer"; */
import GoTop from "@inotom/vue-go-top";

export default {
  name: "App",
  components: {
    Navbar,
    /* Footer, */
    GoTop,
  },
  data: () => ({
    //
  }),
};
</script>

<style lang="scss">
.breadcrub-sheet {
  box-shadow: 0 8px 10px -9px rgba(0, 0, 0, 0.05),
    0 3px 14px 2px rgba(0, 0, 0, 0.01), 0 5px 5px -3px rgba(0, 0, 0, 0.05);
}
</style>
