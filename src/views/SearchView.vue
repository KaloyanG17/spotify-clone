<template>
   <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Podcasts to make you smarter
    </button>

    <div class="py-1.5"></div>

    <div class="grid xl:grid-cols-5 lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 gap-6">
      <CategorySelect category="Podcasts" image="https://picsum.photos/id/25/300/300" />
      <CategorySelect category="AudioBooks" image="https://picsum.photos/id/26/300/300" />
      <CategorySelect category="Made For You" image="https://picsum.photos/id/27/300/300" />
      <CategorySelect category="New Release" image="https://picsum.photos/id/28/300/300" />
      <CategorySelect category="Hip-Hop" image="https://picsum.photos/id/29/300/300" />
      <CategorySelect category="Pop" image="https://picsum.photos/id/30/300/300" />
      <CategorySelect category="Mood" image="https://picsum.photos/id/31/300/300" />
      <CategorySelect category="Party" image="https://picsum.photos/id/32/300/300" />
      <CategorySelect category="Dance" image="https://picsum.photos/id/33/300/300" />
      <CategorySelect category="Workout" image="https://picsum.photos/id/33/300/300" />
      <CategorySelect category="Netflix" image="https://picsum.photos/id/34/300/300" />
      <CategorySelect category="Rock" image="https://picsum.photos/id/35/300/300" />
      <CategorySelect category="Throwback" image="https://picsum.photos/id/36/300/300" />
      <CategorySelect category="R&D" image="https://picsum.photos/id/37/300/300" />
      <CategorySelect category="Country" image="https://picsum.photos/id/38/300/300" />
    </div>
  </div>
</template>

<script setup>
import CategorySelect from '../components/CategorySelect.vue';
</script>
