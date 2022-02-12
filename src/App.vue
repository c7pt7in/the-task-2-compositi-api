<template>
  <div id="app">
    <Calendar />
  </div>
</template>

<script>
import Calendar from './components/Calendar.vue'

export default {
  components: {
    Calendar,
  },
}
</script>

<style>
html,
body,
#app {
  height: 100%;
}
#app {
  background: #e7fdf3;
  padding-top: 20px;
}
</style>
