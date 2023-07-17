<template>
  <v-app white>
    <div><Header /></div>

    <v-main>
      <router-view />
    </v-main>

    <v-footer> <Footer /></v-footer>
  </v-app>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Footer,
  },

  data: () => ({
    //
  }),
};
</script>
