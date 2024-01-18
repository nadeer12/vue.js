<!-- App.vue -->
<template>
  <div id="app">
    <BiometricAuth />
  </div>
</template>

<script>
import BiometricAuth from '@/components/BiometricAuth.vue';

export default {
  components: {
    BiometricAuth,
  },
};
</script>
