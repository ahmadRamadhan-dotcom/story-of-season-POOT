<template>
  <div
    id="key-features"
    class="bg-[#a8db90] pb-20 sm:pb-10 xl:pb-20 sm:bg-[url('/bg-grass.png')] grid place-content-center place-items-center"
  >
    <div class="xl:w-[800px] grid place-content-center">
      <img
        src="../assets/keyfeatures-sign.png"
        alt=""
        class="h-[17vh] sm:h-[36vh] md:h-[17vh] lg:h-[22vh] xl:h-[170px]"
      />
    </div>
    <KeyFeaturesCard :featuresData="keyFeaturesData" />
  </div>
</template>

<script setup>
import KeyFeaturesCard from "./KeyFeaturesCard.vue";
const keyFeaturesData = [
  {
    id: 1,
    title: "Cultivate Your Farm, Cultivate Your Town",
    image: "ss_cultivateyourfarm01_thumb.jpg",
    desc: "Tame the wilderness of the peninsula and build your farm from the ground up!  Gather and process materials to fulfill requests and improve Olive Town's infrastructure, upgrade tools, or commission new outfits and accessories",
  },
  {
    id: 2,
    title: "Simple Mechanics, Deep Gameplay",
    image: "ss_simplemechanics01_thumb.jpg",
    desc: "Greenhorn farmers can rest easy with the return of Seedling Mode and Normal Mode.  Veteran players ready to create a bustling farm of their own will find familiar features and facilities with new twists on classic gameplay elements.",
  },
  {
    id: 3,
    title: "A Farm of Endless Possibilities",
    image: "ss_farm01_thumb.jpg",
    desc: "Clear the land, repair old facilities, and place new ones wherever you see fit.  Level up your farming skills and craft a variety of decorations and facilities, from fences and automatic feeders for livestock to sprinklers for crops!",
  },
  {
    id: 4,
    title: "There’s Always Something Going on in Olive Town!",
    image: "ss_olivetown01_thumb.jpg",
    desc: "Participate in local festivals as the town comes to life with over 200 unique events!  Get to know your neighbors better and you may even find love with a special someone among them.",
  },
];
</script>
