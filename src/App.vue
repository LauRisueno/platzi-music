<template lang="pug">
  //- <div id="app">
  //-   <img src="./assets/logo.png" />
  //-   <h1>{{ msg }}</h1>
  //- </div>
  #app
    img(src="./assets/logo.png")
    h1 {{msg}}
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      msg: "Hello Vue!"
    };
  }
};
</script>
<style lang="scss">
@import './scss/main.scss';
</style>