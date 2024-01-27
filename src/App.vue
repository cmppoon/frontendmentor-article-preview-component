<script setup>
import CardContent from "./components/CardContent.vue";
</script>

<template>
  <main class="min-h-screen flex place-items-center bg-light-grayish-blue">
    <div class="mx-auto p-8 max-sm:max-w-96">
      <div class="flex flex-col sm:flex-row shadow-custom rounded-lg relative">
        <div class="max-h-48 sm:min-w-56 sm:max-w-80 sm:h-auto sm:max-h-max">
          <img
            src="./assets/drawers.jpg"
            alt="drawers image"
            class="rounded-t-lg sm:rounded-l-lg w-full h-full"
          />
        </div>
        <CardContent> </CardContent>
      </div>
    </div>
  </main>
</template>
