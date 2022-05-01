<template>
  <!-- <v-container> -->
    <v-tabs v-model="tab" active-class="active-tab" hide-slider>
      <v-tab class="tab-header">Details</v-tab>
      <v-tab class="tab-header">Delivery</v-tab>
      <v-tab class="tab-header">Fit</v-tab>
      <v-tab class="tab-header">Share</v-tab>
      <v-tab-item>
        <v-card flat>
          <v-card-text class="pa-0">
            <p>
              The Forte Lurex Linen Viscose Jacket in Mother of Pearl features
              lunar lavishness by night and by day: a blazer in a linen blend
              shot with lurex for a shimmering surface that shines like a star
              in the sky. it has a straight fit with well defined shoulders and
              a shawl collar culminating in a button and has been flawlessly
              finished with three jet pockets with a sartorial feel.
            </p>

            <p>See the <a> EDITOR'S NOTE </a></p>
            <p>Learn about the <a>DESIGNER</a></p>
          </v-card-text>
        </v-card>
      </v-tab-item>
      <v-tab-item>
        <v-card flat>
          <v-card-text> Delivery here </v-card-text>
        </v-card>
      </v-tab-item>
      <v-tab-item>
        <v-card flat>
          <v-card-text> fit here </v-card-text>
        </v-card>
      </v-tab-item>
      <v-tab-item>
        <v-card flat>
          <v-card-text> Share here </v-card-text>
        </v-card>
      </v-tab-item>
    </v-tabs>
  <!-- </v-container> -->
</template>

<script>
export default {
  name: "LeftPane",

  data: () => {
    return {
      tab: null,
      text: "",
    };
  },
};
</script>

<style scoped>
.tab-header {
  font-family: Helvetica;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 120%;
  text-transform: uppercase;
  padding: 4px;
}

.v-tab.active-tab {
  font-weight: 700;
  color: #000000;
}

.v-card__text {
  padding-top: 0px;
  text-align: left;

  font-family: Roboto;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 140%;
}

.v-card__text a {
  color: #000000;
  text-decoration: underline;
  font-weight: 400;
}
</style>
>
