<template>
  <header class="text-[4rem] flex flex-col flex-wrap">
    <span
      class="text-[1.5rem] text-pretty sm:text-[2rem] md:text-[3rem] lg:text-[4rem] internalFont"
    >
      {{ title }}
    </span>
    <span class="text-lg">{{ subTitle }}</span>
  </header>
</template>

<script setup>
const props = defineProps({
  title: String,
  subTitle: String,
})
</script>
