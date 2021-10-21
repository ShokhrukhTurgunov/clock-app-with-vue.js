<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from '@/views/Home.vue';

export default {
  components: {
    Home,
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap');

html{
  box-sizing: border-box;
}

body{
  font-family: "Inter", "Arial", sans-serif;
  margin: 0;
  padding: 0;
  color: #FFFFFF;
}

.container{
  width: 100%;
  max-width: 1110px;
  margin: 0 auto;
}

</style>
