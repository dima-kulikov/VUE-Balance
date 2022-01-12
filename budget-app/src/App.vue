<template>
  <div id="app">
    <budjet-list></budjet-list>
  </div>
</template>

<script>
import BudjetList from "./components/BudjetList.vue";

export default {
  name: 'app',
  components: {
    BudjetList,
  },
  data: () => ({
    list:{
    1: {
      type: 'INCOME',
      value: 100,
      comment: 'Some comment',
      id: 1,
    },
     2: {
      type: 'OUTCOME',
      value: -50,
      comment: 'Some outcome comment',
      id: 2,
    },
    }
  }),
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
