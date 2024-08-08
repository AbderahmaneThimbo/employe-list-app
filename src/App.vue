<template>
  <div id="app">
    <EmployeeList />
  </div>
</template>

<script>
import EmployeeList from './components/EmployeeList.vue';

export default {
  name: 'App',
  components: {
    EmployeeList
  }
};
</script>

<style>
body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f5f5f5;
}
</style>
