<script setup>
import FacebookIcon from "./FacebookIcon.vue";
import PinterestIcon from "./PinterestIcon.vue";
import TwitterIcon from "./TwitterIcon.vue";
</script>

<template>
  <div
    class="z-10 absolute right-0 bottom-0 sm:bottom-16 sm:-right-[3.32rem] w-full sm:w-auto flex justify-start sm:justify-center gap-4 p-[1.1rem] px-8 bg-very-dark-grayish-blue rounded-lg"
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
