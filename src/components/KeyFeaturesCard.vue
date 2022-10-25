<template>
  <div
    v-for="(data, index) in featuresData"
    :key="index"
    id="key-features-card"
    class="w-11/12 sm:w-[580px] md:w-[630px] lg:w-[750px] xl:w-[810px] mt-10 sm:mt-9 xl:mt-10"
  >
    <p
      class="font-['astounder-squared-bb'] text-center text-[25px] mx-auto sm:mx-0 w-8/12 sm:w-full sm:text-[28px] font-normal text-[#673e2c]"
    >
      {{ data.title }}
    </p>
    <div class="md:flex md:gap-4 xl:flex xl:gap-4 mt-5 sm:mt-5">
      <img
        :src="'/' + data.image"
        alt=""
        class="sm:h-[68vh] md:h-[160px] lg:h-[190px] xl:h-52 border-2 border-white p-[1px] sm:shadow-md md:shadow-lg"
      />
      <p
        class="text-[#673e2c] mt-5 sm:mt-7 md:mt-0 text-center sm:text-center md:text-left text-lg sm:text-lg font-[300] font-['Ubuntu']"
      >
        {{ data.desc }}
      </p>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  featuresData: Array,
});
</script>
