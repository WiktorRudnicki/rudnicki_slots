<template>
  <div class="layout">
    <AppLayout>
      <AppButton><img src="home.svg" /> Home</AppButton>
    </AppLayout>
  </div>
</template>

<script>
import AppLayout from '../components/AppLayout.vue';
import AppButton from '../components/AppButton.vue';

export default {
  name: 'App',
  components: {
    AppButton,
    AppLayout,
  },
  data: () => ({}),
};
</script>

<style>
.layout {
  display: flex;
}
</style>
