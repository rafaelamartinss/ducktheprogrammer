<template>
  <div>{{}}</div>
</template>
<script setup lang="ts">
const route = useRoute();

const topics = [
  {
    title: "Topic",
    description: "Topic description",
    subtopics: [
      { title: "Topic", description: "Topic description" },
      { title: "subTopic", description: "Topic description" },
    ],
  },
  {
    title: "Topic",
    description: "Topic description",
    subtopics: [
      { title: "Topic 2", description: "Topic description 2" },
      { title: "subTopic 2", description: "subTopic description 2" },
    ],
  },
];
// When accessing /posts/1, route.params.id will be 1
console.log(route.params.id);
</script>
