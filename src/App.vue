<script lang="ts">
import { defineComponent } from "vue";
import AppLayout from "./layouts/AppLayout.vue";

export default defineComponent({
  components: { AppLayout }
})
</script>

<template>
  <AppLayout>
    <router-view />
  </AppLayout>
</template>

<style>
</style>
