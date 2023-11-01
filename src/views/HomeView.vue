<style lang="scss">
.home{
  height: 100vh;
}
</style>
<template>
  <div class="home">
    <navigation />
  </div>
</template>

<script>
import Navigation from './Navigation.vue';
export default {
  name: 'HomeView',
  components: {Navigation}
}
</script>
