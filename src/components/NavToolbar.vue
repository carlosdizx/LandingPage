<template>
  <v-app-bar absolute color="primary" dark>
    <v-img
      class="mx-5"
      src="@/assets/logo.png"
      max-width="60"
      max-height="60"
      alt="logo"
    />
    <v-toolbar-title>Inventas</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn icon>
      <v-icon>mdi-magnify</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon>mdi-heart</v-icon>
    </v-btn>
    <v-btn icon>
      <v-icon>mdi-login</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "NavToolbar",
  data: () => ({}),
});
</script>

<style scoped></style>
