<template>
  <h1 v-text="title"></h1>
  <p>{{ greet }} {{ name }}</p>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      title : 'Practice for Binding Text',
      name : 'Jahid',
      greet : 'Hello',
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
