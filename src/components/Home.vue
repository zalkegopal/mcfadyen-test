<template>
  <v-container class="main-container">
    <v-row>
      <v-col cols="4" class="left-pane"> <left-pane /> </v-col>
      <v-col cols="5" class="imagery"> <imagery /> </v-col>
      <v-col cols="3"> <right-pane /></v-col>
    </v-row>
    <v-container class="footer">
      <h3>A note from the editor</h3>
      <p>
        The Forte Lurex Linen Viscose Jacket in Mother of Pearl features lunar
        lavishness by night and by day: a blazer in a linen blend shot with
        lurex for a shimmering surface that shines like a star in the sky.
      </p>
      <p class="subtext">By <a>MINNA SHIM</a>, Fashion Editor</p>
    </v-container>
  </v-container>
</template>

<script>
import LeftPane from "./LeftPane.vue";
import RightPane from "./RightPane.vue";
import Imagery from "./Imagery.vue";

export default {
  name: "Home",
  components: {
    LeftPane,
    RightPane,
    Imagery,
  },
};
</script>

<style lang="scss" scoped>
.col {
  /* border: 1px dotted black; */
  padding: 0;
}

@media (min-width: 1480px) {
  .main-container {
    max-width: 1400px;
  }
}

@media (min-width: 1264px) {
  .container {
    max-width: 1220px;
  }
}

.footer {
  max-width: 80vw;
  margin-top: 100px;
}

h3 {
  text-transform: uppercase;
  font-weight: 700;
  font-size: 14px;
  line-height: 120%;
  margin-bottom: 24px;
}
p {
  font-size: 28px;
  line-height: 140%;
  text-align: center;

  &.subtext {
    font-size: 14px;
  }
}
</style>
