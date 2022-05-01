<template>
  <ul class="nav-menu">
    <li>The Edit</li>
    <li>New Arrivals</li>
    <li>Designers</li>
    <li>Clothing</li>
    <li>Shoes</li>
    <li>Bags</li>
    <li>Accessories</li>
    <li>Jewelry</li>
    <li>Beauty</li>
    <li>Home</li>
  </ul>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
ul {
  display: inline;
  list-style: none;
}

li {
  font-family: Helvetica;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 120%;
  text-transform: uppercase;
  display: inline-block;
  padding: 8px;
}

li:hover {
    background: #e4e4e4;
}

@media only screen and (max-width: 600px) {
  ul {
    display: none;
  }
}
</style>
