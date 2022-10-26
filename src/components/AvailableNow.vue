<template>
  <div
    class="grid place-content-center 2xl:w-[1600px] 2xl:mx-auto 2xl:bg-[#fff] 2xl:border-[3px]"
  >
    <div class="grid place-content-center place-items-center">
      <img
        src="../assets/availablenow.png"
        class="h-[100px] sm:h-[16vw] md:h-[13vw] lg:h-[12vw] xl:h-[9vw] -translate-y-14 sm:-translate-y-14"
        alt="available board"
      />
    </div>
    <div
      class="grid place-content-center place-items-center sm:grid sm:place-content-center sm:place-items-center lg:flex lg:items-center lg:gap-5 xl:gap-8"
    >
      <img
        src="../assets/tree2.png"
        class="hidden sm:hidden lg:block lg:h-60 lg:-translate-y-20 lg:translate-x-16"
        alt=""
      />
      <h1
        class="text-center text-[32px] sm:text-[38px] lg:text-[45px] leading-[40px] sm:leading-[50px] w-11/12 sm:w-10/12 md:w-8/12 lg:w-[550px] lg:-translate-y-[60px] lg:translate-x-12 sm:text-center font-[300] font-['astounder-squared-bb'] text-[#84b46d]"
      >
        The long-awaited brand new entry in the STORY OF SEASONS series makes
        its debut on Nintendo Switch™!
      </h1>
      <img
        src="../assets/horse.png"
        class="h-32 sm:h-32 mt-10 sm:mt-10"
        alt="nice horses"
      />
      <img
        src="../assets/tree1.png"
        alt=""
        class="hidden sm:hidden lg:block lg:-translate-y-[210px] lg:-translate-x-24 lg:h-60"
      />
    </div>
  </div>
  <div class="green-zigzag">&nbsp;</div>
</template>

<style scoped>
.green-zigzag {
  background-size: 30px 30px;
  height: 30px;
}
.green-zigzag {
  background-image: linear-gradient(44deg, #a8db90 52%, transparent 52%),
    linear-gradient(317deg, #a8db90 52%, transparent 52%);
}
</style>
