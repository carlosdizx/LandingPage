<template>
  <v-container>
    <CarouselItems />
  </v-container>
</template>

<script lang="ts">
import CarouselItems from "@/components/CarouselItems.vue";
import { Component, Vue } from "vue-property-decorator";

@Component({
  components: { CarouselItems },
})
export default class HomeView extends Vue {}
</script>
