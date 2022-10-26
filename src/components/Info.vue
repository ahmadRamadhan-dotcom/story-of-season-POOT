<template>
  <div
    id="info-section"
    class="sm:flex sm:justify-center xl:flex xl:justify-center xl:items-center bg-[url('/wood.jpg')] py-16 sm:py-20 xl:h-[30vw] 2xl:w-[1600px] 2xl:mx-auto"
  >
    <div
      class="hidden sm:w-[578px] md:w-[700px] lg:w-[770px] xl:w-[800px] sm:flex xl:grid xl:grid-cols-2 sm:border-dashed sm:border-[3px] sm:border-[#673e2c]"
    >
      <div
        class="grid sm:w-52 xl:w-52 border-r-2 border-dashed border-[#673e2c] text-right text-[#fff]"
      >
        <p
          v-for="(data, index) in leftTable"
          :key="index"
          id="left-table"
          :class="data.id == 6 ? 'border-b-0' : 'sm:border-b-[3px]'"
          class="tracking-[0.1em] font-['astounder-squared-lc-bb'] sm:pr-3 xl:pr-3 font-[300] sm:text-[26px] xl:text-[26px] sm:border-dashed sm:border-[#673e2c]"
        >
          {{ data.name }} :
        </p>
      </div>
      <div
        class="sm:translate-x-[1px] xl:-translate-x-[200px] sm:w-[400px] md:w-[550px] xl:w-[600px]"
      >
        <p
          v-for="(data, index) in rightTable"
          :key="index"
          :class="data.id === 6 ? ' border-b-0' : 'sm:border-b-[3px]'"
          id="right-table"
          class="tracking-[0.1em] sm:border-dashed border-[#673e2c] md:p-2 xl:p-[6px] sm:pl-5 xl:pl-7 font-['astounder-squared-lc-bb'] font-[300] sm:text-[26px] xl:text-[26px] text-[#673e2c]"
        >
          {{ data.name }}
        </p>
      </div>
    </div>
    <div
      class="grid place-content-center text-center place-items-center tracking-[0.1em] sm:hidden"
    >
      <p
        id="full-list"
        v-for="(data, index) in fullList"
        :key="index"
        class="font-['astounder-squared-lc-bb'] leading-[38px] w-9/12 font-[300] even:text-[24px] odd:text-[29px] even:text-[#673e2c] odd:text-[#fff]"
      >
        {{ data.name }}
      </p>
    </div>
  </div>
</template>

<script>
const leftTable = [
  { id: 1, name: "Title" },
  { id: 2, name: "Publisher" },
  { id: 3, name: "Platform" },
  { id: 4, name: "Release Date" },
  { id: 5, name: "Genre" },
  { id: 6, name: "Players" },
];

const rightTable = [
  { id: 1, name: "STORY OF SEASONS : Pioneers of Olive Town" },
  { id: 2, name: "XSEED Games" },
  { id: 3, name: "Nintendo Switch / PS4 / STEAM" },
  { id: 4, name: "March 23, 2021" },
  { id: 5, name: "Simulation" },
  { id: 6, name: "1 Player" },
];

const fullList = [
  { id: 1, name: "Title" },
  { id: 2, name: "STORY OF SEASONS : Pioneers of Olive Town" },
  { id: 3, name: "Publisher" },
  { id: 4, name: "XSEED Games" },
  { id: 5, name: "Platform" },
  { id: 6, name: "Nintendo Switch / PS4 / STEAM" },
  { id: 7, name: "Release Date" },
  { id: 8, name: "March 23, 2021" },
  { id: 9, name: "Genre" },
  { id: 10, name: "Simulation" },
  { id: 11, name: "Players" },
  { id: 12, name: "1 Players" },
];

export default {
  name: "Info",
  data() {
    return {
      leftTable,
      rightTable,
      fullList,
    };
  },
};
</script>

<style scoped>
#left-table {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.7);
}

#right-table {
  text-shadow: 1px 1px 0 rgba(255, 255, 255, 0.7);
}

#full-list:nth-child(even) {
  text-shadow: 1px 1px 0 rgba(255, 255, 255, 0.7);
}

#full-list:nth-child(odd) {
  text-shadow: 1px 1px 0 rgba(0, 0, 0, 0.7);
}
</style>
