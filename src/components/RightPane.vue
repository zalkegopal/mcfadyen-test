<template>
  <v-container class="details-container">
    <v-card flat>
      <v-card-title class="mb-1"> JONATHAN SIMKHAI </v-card-title>
      <v-card-subtitle
        >Lurex Linen Viscose Jacket in Conchiglia
        <h3 class="mt-2">$225</h3>
      </v-card-subtitle>
      <v-card-text>
        <h3 class="mt-2 text-uppercase">Color <span> Conchiglia </span></h3>
        <v-row class="small-img-row">
          <v-col class="img-left pa-0"
            ><v-img src="../assets/svgs/girlsmall1.svg"
          /></v-col>
          <v-col class="img-right pa-0 pt-1"
            ><v-img src="../assets/svgs/girlsmall2.svg"
          /></v-col>
        </v-row>
        <div class="d-flex justify-space-between mt-8 text-uppercase">
          <h3>Size</h3>
          <span> &nbsp; L </span> <v-spacer />
          <a href="/size-guide"> Size guide</a>
        </div>
        <div class="size-selector mt-2">
          <v-btn class="btn" outlined rounded>XXS</v-btn>
          <v-btn class="btn" outlined rounded>S</v-btn>
          <v-btn class="btn" outlined rounded>M</v-btn>
          <v-btn class="btn solid" rounded>L</v-btn>
        </div>
        <div class="size-selecto mt-2">
          <v-btn class="btn" outlined rounded>XXL</v-btn>
        </div>

        <v-btn class="btn solid add-btn" rounded>ADD TO BAG</v-btn>
        <p class="mt-6">
          Get 4 interest-free payments of $196.25 with Klarna <a>LEARN MORE</a>
        </p>
        <p>Speak to a Personal Stylist <a>CHAT NOW</a></p>
      </v-card-text>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "RightPane",
};
</script>

<style lang="scss" scoped>
.details-container {
  padding: 0;
}

.v-card {
  font-family: "Roboto";
  font-style: normal;
  text-align: left;
  font-size: 14px;
  font-weight: 400;
  white-space: normal;
}

h3 {
  font-size: 14px;

  span {
    font-weight: 400;
  }
}

.v-card__title {
  margin-top: 80px;
  font-size: 48px;
  line-height: 96%;
  /* or 46px */

  letter-spacing: -0.04em;
  text-transform: uppercase;
}

.small-img-row {
  width: 60%;
  margin-top: 8px;
  padding-left: 14px;

  .img-left {
    border: 1px solid #000000;
    margin-right: 4px;
  }
  .img-right {
    border: 1px solid lightgray;
  }
}

.size-selector {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
}

.btn {
  border: 1px solid #e5e5e5;
  box-sizing: border-box;
  padding: 8px 24px;

  &.solid {
    background: #000000;
    color: white;
  }

  &.add-btn {
    height: 48px;
    width: 100%;
    margin-top: 32px;
  }
}
</style>
