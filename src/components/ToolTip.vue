<script setup>
import FacebookIcon from "./FacebookIcon.vue";
import PinterestIcon from "./PinterestIcon.vue";
import TwitterIcon from "./TwitterIcon.vue";
</script>

<template>
  <div
    class="absolute right-0 bottom-0 sm:bottom-14 sm:-right-[6.3rem] w-full sm:w-auto z-10 flex justify-start sm:justify-center gap-4 p-4 px-8 bg-very-dark-grayish-blue rounded-lg"
  >
    <div class="flex items-center">
      <p class="text-[11px] font-medium text-grayish-blue tracking-[0.2rem]">
        SHARE
      </p>
    </div>
    <FacebookIcon></FacebookIcon>
    <TwitterIcon></TwitterIcon>
    <PinterestIcon></PinterestIcon>
    <div
      class="invisible sm:visible absolute w-4 h-4 bg-very-dark-grayish-blue rotate-45 inset-x-24 inset-y-10"
    ></div>
  </div>
</template>
