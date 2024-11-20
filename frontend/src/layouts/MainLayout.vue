<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container class="background_dark_blue">
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup lang="ts">
defineOptions({
  name: 'MainLayout'
});
</script>
