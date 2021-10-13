<template>
  <div id="app">
    <AppButton text="Home"></AppButton>
  </div>
</template>

<script>
import AppButton from '@/components/AppButton.vue';

export default {
  name: 'App',

  data: () => ({
    //
  }),

  components: {
    AppButton,
  },
};
</script>
