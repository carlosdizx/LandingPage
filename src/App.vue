<template>
  <v-app>
    <NavToolbar />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import NavToolbar from "./components/NavToolbar.vue";
import Vue from "vue";

export default Vue.extend({
  name: "App",

  components: {
    NavToolbar,
  },

  data: () => ({}),
});
</script>
