<template>
  <v-app>
    <v-app-bar elevation="0" app color="white" light>
      <div class="d-flex align-center">
        <h1 class="company-name">MY COMPANY.COM</h1>
      </div>

      <v-spacer></v-spacer>
      <Navbar />
      <v-spacer></v-spacer>

      <div class="nav-actions">
        <v-btn icon>
          <v-icon>mdi-magnify</v-icon>
        </v-btn>
        <v-btn icon>
          <v-icon>mdi-cart-outline</v-icon>
        </v-btn>
        <v-btn icon>
          <v-icon>mdi-account-outline</v-icon>
        </v-btn>
      </div>
    </v-app-bar>

    <v-main>
      <Home />
    </v-main>
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Home from "./components/Home.vue";

export default {
  name: "App",

  components: {
    Navbar,
    Home,
  },
};
</script>

<style>
#app {
  font-family: Roboto, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  background: #ffffff;
  margin-top: 60px;
}

.v-main {
  padding: 0px 0px 0px !important;
}

.company-name {
  font-family: Roboto;
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  line-height: 100%;
  /* identical to box height, or 20px */
  text-transform: uppercase;
  color: #000000;
}

.v-application a {
  color: #000000 !important;
  text-decoration: underline !important;
}
</style>
