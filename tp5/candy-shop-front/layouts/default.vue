<template>
  <div>
    <Header/>
    <div>
      <nuxt/>
      <login/>
      <signup/>
      <checkout/>
    </div>
    <Footer/>
  </div>
</template>

<script>
import Header from "../components/layout/Header";
import Footer from "../components/layout/Footer";
import Login from "../components/auth/Login";
import Signup from "../components/auth/Signup";
import Checkout from "../components/auth/Checkout";

export default {
  components: {
    Checkout,
    Signup,
    Login,
    Footer,
    Header,
  }
}
</script>

<style>
body {
  @apply flex;
  @apply flex-col;
  height: 100vh;
  margin: 0;
}
</style>
