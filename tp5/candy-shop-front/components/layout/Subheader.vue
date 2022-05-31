<template>
  <div class="m-4 p-4 text-center">
    <search/>
  </div>
</template>

<script>
  import Search from "../Search";

  export default {
    name: 'subheader',

    components: {
      Search,
    }
  }
</script>
