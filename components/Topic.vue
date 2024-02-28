<template>
  <div>
    <nuxt-link :to="props.link">
      <span>{{ props.title }}</span>
    </nuxt-link>
  </div>
</template>
<script setup lang="ts">
const props = defineProps({
  title: {
    type: String,
  },
  link: {
    type: String,
  },
});
</script>
