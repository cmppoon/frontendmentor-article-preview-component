<script setup>
import ShareIcon from "./ShareIcon.vue";
</script>

<template>
  <div
    class="flex flex-col justify-between p-8 sm:px-12 bg-white gap-4 rounded-b-lg sm:rounded-r-lg text-[13px] font-bold tracking-wide sm:w-[30rem]"
  >
    <h1 class="text-sm sm:text-xl text-very-dark-grayish-blue">
      Shift the overall look and feel by adding these wonderful touches to
      furniture in your home
    </h1>
    <h2 class="text-desaturated-dark-blue font-medium">
      Ever been in a room and felt like something was missing? Perhaps it felt
      slightly bare and uninviting. I’ve got some simple tips to help you make
      any room feel complete.
    </h2>
    <div class="flex flex-row justify-between items-center mt-4">
      <div class="flex flex-row gap-4">
        <div class="my-auto">
          <img
            src="../assets/avatar-michelle.jpg"
            alt="avartar"
            class="rounded-full w-10 h-10"
          />
        </div>
        <div class="text-sm">
          <p class="text-very-dark-grayish-blue">Michelle Appleton</p>
          <p class="text-grayish-blue font-medium">28 Jun 2020</p>
        </div>
      </div>
      <div>
        <ShareIcon> </ShareIcon>
      </div>
    </div>
  </div>
</template>
