<template>
  <div style="display: flex">
    <Sheet style="margin-left: 20px">
      <h3>Memo to myself</h3>
      <p>Always prepare for PLFs in time!</p>
      <img src="info.svg" width="80px" />
    </Sheet>
    <Sheet style="margin-left: 20px">
      <p>INSY, SEW and Webtechnologies are our favorite subjects!</p>
      <span style="font-style: italic">Starkschwitz Fiedler, Jan Schreck</span>
      <p>Wish you were here</p>
      <span style="font-style: italic">E. Wahn</span>
    </Sheet>
  </div>
</template>

<script>
import Sheet from '../components/Sheet.vue';

export default {
  name: 'App',
  components: {
    Sheet,
  },
  data: () => ({}),
};
</script>
