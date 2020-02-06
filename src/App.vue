<template>
  <div id="app">
    <child>
      <h2>This is the projected content!</h2>
    </child>
  </div>
</template>

<script>
import child from "@/components/child";
export default {
  name: "App",
  components: { child }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
<style scoped>
h2 {
  color: #0072BC;
}
</style>
