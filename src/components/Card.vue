<script setup>
defineProps({
  imageUrl: String,
  field: String,
  readTime: Number,
  title: String,
  text: String
})
</script>

<template>
  <div
    class="mt-10 bg-white rounded-3xl transition hover:-translate-y-2 hover:shadow-xl cursor-pointer min-w-96 max-w-96"
  >
    <div><img :src="imageUrl" alt="banner img" /></div>
    <div class="p-8">
      <div class="flex justify-between items-center">
        <span class="px-3 py-2 bg-lime-400 rounded-full">{{ field }}</span>
        <span class="text-slate-500">{{ readTime }} min read</span>
      </div>

      <div class="mt-5">
        <h3 class="text-2xl">
          <b>{{ title }}</b>
        </h3>
        <p class="mt-3">{{ text }}</p>
      </div>

      <div class="mt-5">
        <span class="cursor-pointer text-lime-400 text-lg">Read more ></span>
      </div>
    </div>
  </div>
</template>
