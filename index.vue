<template lang="pug">
  <notifications />
</template>
<script lang="ts">
import Notifications from '@kyvg/vue3-notification'
import Vue from 'vue'
Vue.use(Notifications)

Vue.notify({
    title: "Error",
    text: "Test error",
  });
  </script>