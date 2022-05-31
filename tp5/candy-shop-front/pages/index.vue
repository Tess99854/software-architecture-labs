<template>
  <div>
    <hero/>
    <subheader/>
    <products-list/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Hero from "~/components/layout/Hero.vue";
import Subheader from "~/components/layout/Subheader.vue";
import ProductsList from "~/components/ProductsList.vue";

export default Vue.extend({
  name: 'IndexPage',
  components: {ProductsList, Subheader, Hero}
})
</script>
