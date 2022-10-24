<template>
  <div
    id="banner-hero"
    class="sm:bg-[url('/keyvisual.jpg')] bg-no-repeat bg-cover bg-[center_center] sm:h-[60vw] xl:h-[47vw]"
  >
    <div class="sm:flex sm:justify-between xl:flex xl:justify-between xl:p-1">
      <div
        class="sm:flex sm:items-center sm:gap-1 xl:flex xl:gap-2 xl:items-center"
      >
        <img
          class="sm:h-14 xl:h-20"
          src="../assets/nintendoswitch.jpg"
          alt="cool nintendo switch logo"
        />
        <div class="flex lg:flex-row-reverse xl:flex-row gap-1 items-center">
          <img
            src="../assets/ps4.png"
            alt="nice ps4 logo"
            class="sm:h-7 xl:h-9"
          />
          <img
            src="../assets/steam.png"
            alt="another cool logo from steam"
            class="sm:h-10 xl:h-12"
          />
        </div>
      </div>
      <div
        class="sm:mr-32 sm:translate-y-12 sm:-translate-x-9 lg:translate-y-24 xl:translate-y-16 xl:mr-[200px]"
      >
        <img
          src="../assets/gamelogo.png"
          alt="story of season : pioneers of olive town"
          class="sm:h-[60px] lg:h-20"
        />
      </div>
      <img
        src="../assets/25thanniversary.png"
        alt=""
        class="sm:hidden xl:block h-20 xl:translate-y-2"
      />
      <img
        src="../assets/mobinav.png"
        alt=""
        class="sm:h-[60px] xl:hidden sm:translate-y-1"
      />
    </div>
  </div>
</template>
