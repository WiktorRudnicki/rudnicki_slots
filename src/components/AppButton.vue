<template>
    <div>
        <button v-on="$listeners"><slot /></button>
    </div>
</template>

<script>
export default {
  name: 'AppButton',
};
</script>
