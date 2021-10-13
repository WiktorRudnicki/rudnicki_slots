<template>
  <div id="app">
    <AppButton @click="handle"><img src='home.svg' /> Home</AppButton>
    <br />
    <AppButton>About <img src='info.svg' /> Me</AppButton>
  </div>
</template>

<script>
import AppButton from './components/AppButton.vue';

export default {
  name: 'App',

  data: () => ({
    components: {
      AppButton,
    },
  }),
};
</script>
