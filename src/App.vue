<template>
  <MainHeader title="RememberMe" />
  <ResourceTabs />
</template>

<script>
import MainHeader from './components/layouts/MainHeader.vue';
import ResourceTabs from './components/learning-resources/ResourcesTabs.vue';

export default {
  components: {
    MainHeader,
    ResourceTabs,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Roboto', sans-serif;
}

body {
  margin: 0;
}
</style>
