<template>
  <header
    class="sm:hidden xl:block xl:flex xl:justify-center bg-no-repeat xl:bg-[url('/header-background.webp')] xl:p-[8px_8px] bg-[center_center] bg-cover"
  >
    <div class="xl:flex xl:gap-5">
      <span
        v-for="(data, index) in headerList"
        :key="index"
        class="font-['astounder-squared-bb'] font-[300] text-[#ffffff] text-2xl"
        >{{ data.name }}
      </span>
    </div>
  </header>
</template>

<script setup>
const headerList = [
  { id: 1, name: "Features" },
  { id: 2, name: "Cast" },
  { id: 3, name: "Build your Farm" },
  { id: 4, name: "Life In Olive Town" },
  { id: 5, name: "Take Pics And Share" },
  { id: 6, name: "Expansion Pass" },
  { id: 7, name: "Buffy's Journey" },
  { id: 8, name: "Sourvenirs" },
];
</script>

<style scoped>
header {
  border-bottom: 3px solid rgba(0, 0, 0, 0.3);
}
</style>
