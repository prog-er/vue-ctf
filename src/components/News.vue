<script setup>
import Card from './Card.vue'
</script>

<template>
  <div class="mt-36">
    <h2 class="text-5xl text-center">Stay updated with CTF</h2>
    <div class="flex justify-center mt-8">
      <h3 class="text-2xl max-w-xl text-center">
        Get the latest news and insights about CTF events and cybersecurity trends
      </h3>
    </div>

    <div class="gap-4 flex overflow-x-auto">
      <Card
        imageUrl="/public/ph-1.svg"
        field="Cybersecurity"
        :readTime="2"
        title="The importance of cybersecurity"
        text="Learn why cybersecurity is crucial in protecting sensitive information and preventing cyber attacks"
      />
    </div>
  </div>
</template>
