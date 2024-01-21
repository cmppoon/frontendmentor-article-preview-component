<script setup>
import { ref, computed } from "vue";
import ToolTip from "./ToolTip.vue";

const isActive = ref(false);
const onClick = () => {
  isActive.value = !isActive.value;
};

const colorClass = computed(() => ({
  "fill-[#6E8098]": !isActive.value,
  "fill-white": isActive.value,
}));
</script>

<template>
  <div
    v-on:click="onClick"
    class="rounded-full w-9 h-9 bg-light-grayish-blue relative select-none"
    :class="{ 'bg-very-dark-grayish-blue': isActive }"
  >
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="15"
      height="13"
      class="absolute inset-y-[10.3px] inset-x-[11.2px]"
      :class="colorClass"
    >
      <path
        d="M15 6.495L8.766.014V3.88H7.441C3.33 3.88 0 7.039 0 10.936v2.049l.589-.612C2.59 10.294 5.422 9.11 8.39 9.11h.375v3.867L15 6.495z"
      />
    </svg>

    <Transition
      enter-from-class="opacity-0"
      enter-active-class="transition duration-300"
      leave-to-class="opacity-0"
      leave-active-class="transition duration-300"
    >
      <ToolTip v-if="isActive"> </ToolTip>
    </Transition>
  </div>
</template>
