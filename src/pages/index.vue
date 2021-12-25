<script setup lang="ts">
import {
  kButton,
  kApp,
} from 'konsta/vue'

</script>

<template>
  <k-app theme="material">
    <div class="m-32 mx-auto max-w-5xl">
      <k-button>Button</k-button>
    </div>
  </k-app>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
