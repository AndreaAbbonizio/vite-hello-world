<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  data() {
    return {
      message: 'ciao',
    };
  },
  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <AppTitle></AppTitle>
  <AppHero></AppHero>
</template>

<style></style>