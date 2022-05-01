<template>
  <v-container>
    <v-row class="mt-6">
      <v-col><v-img src="../assets/svgs/girl1.svg" /></v-col
    ></v-row>
    <v-row>
      <v-col cols="6" class="pt-0"
        ><v-img src="../assets/svgs/girl3.svg"
      /></v-col>
      <v-col cols="6" class="pt-0"
        ><v-img src="../assets/svgs/girl4.svg"
      /></v-col>
    </v-row>
    <span class="d-flex justify-center text-uppercase">
      <a>view more like this product</a></span
    >
    <v-row>
      <v-col><v-img src="../assets/svgs/girl2.svg" /></v-col
    ></v-row>
    <v-row>
      <v-col class="pt-0"><v-img src="../assets/svgs/girl5.svg" /></v-col
    ></v-row>
    <v-row class="product-links">
      <v-col class="d-flex justify-center">
        <a>Jonathan Simkhai</a>
        <a>Blazers</a>
        <a>Viscose</a>
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
