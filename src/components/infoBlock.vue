<script setup>
defineProps({
  title: String,
  description: String,
  imageUrl: String,
});
</script>

<template>
  <div class="flex flex-col items-center text-center w-72 mx-auto">
    <img height="80" width="80" :src="imageUrl" alt="info" />
    <h2 class="text-2xl mt-4 font-medium">{{ title }}</h2>
    <p class="text-slate-400 mt-2">{{ description }}}</p>
  </div>
</template>
