<script setup>
import FacebookIcon from "./FacebookIcon.vue";
import PinterestIcon from "./PinterestIcon.vue";
import TwitterIcon from "./TwitterIcon.vue";
</script>

<template>
  <div class="absolute -inset-x-[5.3rem] -inset-y-[4.5rem]">
    <div
      class="z-10 flex justify-center gap-4 p-4 px-14 bg-very-dark-grayish-blue absolute rounded-lg"
    >
      <div class="flex items-center">
        <p class="text-[11px] font-medium text-grayish-blue tracking-[0.2rem]">
          SHARE
        </p>
      </div>
      <FacebookIcon></FacebookIcon>
      <TwitterIcon></TwitterIcon>
      <PinterestIcon></PinterestIcon>
    </div>
    <div
      class="absolute w-4 h-4 bg-very-dark-grayish-blue rotate-45 inset-x-24 inset-y-10"
    ></div>
  </div>
</template>
