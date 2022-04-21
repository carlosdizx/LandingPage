<template>
  <v-card>
    <v-carousel>
      <v-carousel-item :key="i" v-for="i in 5">
        <v-layout>
          <v-flex xs4 :key="j" v-for="j in 3">
            <v-card class="py-9">
              <v-card-title> Titulo {{ j }} </v-card-title>
              <v-card-text>
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s, when an unknown printer took a galley
                of type and scrambled it to make a type specimen book. It has
                survived not only five centuries, but also the leap into
                electronic typesetting, remaining essentially unchanged. It was
                popularised in the 1960s with the release of Letraset sheets
                containing Lorem Ipsum passages, and more recently with desktop
                publishing software like Aldus PageMaker including versions of
                Lorem Ipsum.
              </v-card-text>
              <v-card-actions>
                <v-btn block color="primary">Comprar</v-btn>
              </v-card-actions>
            </v-card>
          </v-flex>
        </v-layout>
      </v-carousel-item>
    </v-carousel>
  </v-card>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "CarouselItems",
});
</script>

<style scoped></style>
