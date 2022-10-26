<template>
  <div
    id="banner-hero"
    class="bg-[url('/keyvisual-v.jpg')] sm:bg-[url('/keyvisual.jpg')] bg-no-repeat bg-cover bg-right-top sm:bg-[center_center] h-[135vw] sm:h-[60vw] xl:h-[49vw] 2xl:h-[35vw] 2xl:w-[1600px] 2xl:mx-auto"
  >
    <div
      class="flex justify-between -translate-y-2 sm:flex sm:justify-between xl:flex xl:justify-between xl:-translate-y-0 xl:p-1"
    >
      <div
        class="flex items-center sm:flex sm:items-center gap-1 sm:gap-1 xl:flex xl:gap-2 xl:items-center"
      >
        <img
          class="h-12 sm:h-14 xl:h-20"
          src="/nintendoswitch.jpg"
          alt="cool nintendo switch logo"
        />
        <div class="flex lg:flex-row-reverse xl:flex-row gap-1 items-center">
          <img src="/ps4.png" alt="nice ps4 logo" class="h-6 sm:h-7 xl:h-9" />
          <img
            src="/steam.png"
            alt="another cool logo from steam"
            class="h-7 sm:h-10 xl:h-12"
          />
        </div>
      </div>
      <div
        class="hidden sm:block -translate-x-3 translate-y-32 sm:mr-32 sm:translate-y-12 sm:-translate-x-9 lg:translate-y-24 xl:translate-y-16 xl:mr-[200px]"
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
        class="hidden sm:hidden xl:block h-20 xl:translate-y-2"
      />
      <img
        src="../assets/mobinav.png"
        alt=""
        class="h-14 sm:h-[60px] xl:hidden translate-y-3 sm:translate-y-1"
      />
    </div>
    <div class="grid sm:hidden place-content-center place-items-center mt-14">
      <img src="../assets/gamelogo.png" alt="" class="h-[70px]" />
    </div>
  </div>
</template>
