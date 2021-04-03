<template>
  <div>
    <div class="app">
      <Nuxt />
    </div>
  </div>
</template>

<style>
html {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.app {
  /* background-color: #009688; */
  background-image: -webkit-linear-gradient(
    180deg,
    #009688 0,
    #009688 127px,
    #dddbd1 127px,
    #dddbd1 127px
  );
  background-image: linear-gradient(
    180deg,
    #009688 0,
    #009688 127px,
    #dddbd1 127px,
    #dddbd1 127px
  );
  min-height: 100vh;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
</style>
