<template>
  <v-container>
    <v-row>
      <v-col class="pt-1">
        <v-carousel
          :continuous="true"
          :show-arrows="false"
          hide-delimiter-background
          delimiter-icon="mdi-minus"
          height="460"
          reverse-transition="fade-transition"
          transition="fade-transition"
        >
          <v-carousel-item>
            <v-img src="../assets/svgs/girl1.svg" />
          </v-carousel-item>
          <v-carousel-item>
            <v-img src="../assets/svgs/girl2.svg" />
          </v-carousel-item>
          <v-carousel-item>
            <v-img src="../assets/svgs/girl3.svg" />
          </v-carousel-item>
          <v-carousel-item>
            <v-img src="../assets/svgs/girl4.svg" />
          </v-carousel-item>
          <v-carousel-item>
            <v-img src="../assets/svgs/girl5.svg" />
          </v-carousel-item>
        </v-carousel>
      </v-col></v-row
    >
  </v-container>
</template>

<script>
export default {
  name: "Imagery",
};
</script>

<style lang="scss" scoped>
.product-links {
  margin-top: 100px;
  a {
    text-transform: uppercase;
    margin: 12px;
  }
}
</style>
