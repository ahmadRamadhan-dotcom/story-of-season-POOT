<template>
  <footer
    class="grid py-7 place-content-center xl:mt-10 2xl:mt-0 2xl:bg-[#fff] 2xl:mx-auto 2xl:border-[3px] 2xl:w-[1600px]"
  >
    <div
      class="w-[98%] mx-auto sm:w-11/12 md:w-10/12 lg:w-9/12 text-center sm:mx-auto flex flex-wrap justify-center sm:flex sm:flex-wrap sm:justify-center sm:gap-1 gap-2 xl:flex xl:gap-5 sm:flex-nowrap place-items-center"
    >
      <img
        v-for="(data, index) in platform"
        :key="index"
        :src="'/' + data.image"
        alt="platform logo"
        :class="data.class"
      />
    </div>
    <div
      class="mt-10 sm:mt-10 mx-auto w-11/12 sm:w-11/12 sm:mx-auto xl:mt-14 text-center grid place-content-center items-center font-[300] font-['Ubuntu'] text-[#000000]"
    >
      <span class="text-[13px]"
        >©2022 Marvelous Inc. All Rights Reserved.
      </span>
      <span class="text-[13px]"
        >Licensed to and published by XSEED Games / Marvelous USA, Inc.
      </span>
      <span class="text-[13px] xl:mt-4"
        >Nintendo Switch is a trademark of Nintendo.
      </span>
      <span class="text-[13px] xl:mt-3"
        >©2021 Valve Corporation. Steam and the Steam logo are trademarks and/or
        registered trademarks of Valve Corporation in the U.S. and/or other
        countries.
      </span>
      <span class="text-[13px] xl:mt-2"
        >The ESRB rating icons are registered trademarks of the Entertainment
        Software Association.
      </span>
    </div>
  </footer>
</template>

<script setup>
const platform = [
  {
    id: 1,
    name: "XSEED Games",
    image: "xseed.png",
    class: "h-4 sm:h-5 xl:h-10",
  },
  {
    id: 2,
    name: "marvelous",
    image: "marvelous.png",
    class: "h-5 sm:h-10",
  },
  {
    id: 3,
    name: "nintedo",
    image: "nintendoswitch.jpg",
    class: "h-8 sm:h-14",
  },
  {
    id: 4,
    name: "nintendo-eshop",
    image: "nintendoeshop.png",
    class: "h-3 sm:h-5 xl:h-6",
  },
  {
    id: 5,
    name: "ps4",
    image: "ps4.png",
    class: "h-4 sm:h-8 xl:h-10",
  },
  {
    id: 6,
    name: "steam",
    image: "steam.png",
    class: "h-6 sm:h-10 xl:h-12",
  },
  {
    id: 7,
    name: "",
    image: "everyone.jpg",
    class: " h-20 xl:h-24",
  },
];
</script>
