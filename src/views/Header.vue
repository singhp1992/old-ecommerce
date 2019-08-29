// header here
// add search option - bootstrap
<template>
  <div class="header" id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/products">Products</router-link> |
    <router-link to="/cart">Shopping Cart</router-link>
  </div>
</template>Î

<script> 
export default {
  name: "header",
  components: {
    
  }
};
</script>

<style>
#nav {
  padding: 30px;
  border: 1px solid black;
  background-color: black;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  color: white;
}

a {
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #d878f0;
}
</style>
