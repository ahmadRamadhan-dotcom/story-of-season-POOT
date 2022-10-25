<template>
  <footer class="grid py-7 place-content-center xl:mt-10">
    <div
      class="sm:w-11/12 md:w-10/12 lg:w-9/12 text-center sm:mx-auto sm:grid sm:grid-cols-6 sm:place-content-center sm:place-items-center xl:flex xl:gap-5 place-items-center"
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
      class="sm:mt-10 sm:w-11/12 sm:mx-auto xl:mt-14 text-center grid place-content-center items-center font-[300] font-['Ubuntu'] text-[#000000]"
    >
      <span class="sm:text-[13px]"
        >©2022 Marvelous Inc. All Rights Reserved.
      </span>
      <span class="sm:text-[13px]"
        >Licensed to and published by XSEED Games / Marvelous USA, Inc.
      </span>
      <span class="sm:text-[13px] xl:mt-4"
        >Nintendo Switch is a trademark of Nintendo.
      </span>
      <span class="sm:text-[13px] xl:mt-3"
        >©2021 Valve Corporation. Steam and the Steam logo are trademarks and/or
        registered trademarks of Valve Corporation in the U.S. and/or other
        countries.
      </span>
      <span class="sm:text-[13px] xl:mt-2"
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
    class: "sm:h-5 xl:h-10",
  },
  {
    id: 2,
    name: "marvelous",
    image: "marvelous.png",
    class: "sm:h-10",
  },
  {
    id: 3,
    name: "nintedo",
    image: "nintendoswitch.jpg",
    class: "sm:h-14",
  },
  {
    id: 4,
    name: "nintendo-eshop",
    image: "nintendoeshop.png",
    class: "sm:h-5 xl:h-6",
  },
  {
    id: 5,
    name: "ps4",
    image: "ps4.png",
    class: "sm:h-8 xl:h-10",
  },
  {
    id: 6,
    name: "steam",
    image: "steam.png",
    class: "sm:h-10 xl:h-12",
  },
  {
    id: 7,
    name: "",
    image: "everyone.jpg",
    class: " xl:h-24",
  },
];
</script>
