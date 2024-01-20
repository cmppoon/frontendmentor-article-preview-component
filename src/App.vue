<script setup>
import CardContent from "./components/CardContent.vue";
</script>

<template>
  <main class="min-h-screen flex place-items-center bg-light-grayish-blue">
    <div class="mx-auto p-8">
      <div class="flex flex-col sm:flex-row shadow-custom">
        <div class="h-60 sm:w-80 sm:h-auto">
          <img
            src="./assets/drawers.jpg"
            alt="drawers image"
            class="rounded-l-lg w-full h-full"
          />
        </div>
        <CardContent> </CardContent>
      </div>
    </div>
  </main>
</template>
