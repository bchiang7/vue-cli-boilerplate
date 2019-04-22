<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/images/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import { HelloWorld } from 'components';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
</script>

<style lang="scss">
@import './styles/main.scss';

#app {
  margin-top: 60px;
  color: $navy;
  text-align: center;
}

img {
  width: auto;
}
</style>
