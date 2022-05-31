<template>
  <div class="cover-img">
    <h1 class="text-white text-6xl mb-5 font-bold">
      Get your favourite candy in the blink of an eye
    </h1>
    <h2 class="text-white text-2xl">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt
    </h2>
  </div>
</template>

<style scope>
.cover-img {
  @apply p-10 lg:p-36 relative;
}
.cover-img:after {
  content: '';
  background: url("assets/cover.jpg") center no-repeat;
  background-size: cover;
  position: absolute;
  top:0;
  left: 0;
  width:100%;
  height:100%;
  z-index:-1;
  opacity: 0.8;
}
</style>
