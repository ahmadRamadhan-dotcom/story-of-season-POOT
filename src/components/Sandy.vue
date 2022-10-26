<template>
  <div
    id="section-sandy"
    class="sm:bg-[url('/bg-sandy.png')] bg-[#ffe8be] sm:h-[135vw] lg:h-[60vw] xl:h-[55vw] flex justify-center 2xl:mx-auto 2xl:w-[1600px]"
  >
    <div class="lg:flex lg:items-center">
      <img
        src="../assets/maincharacters.png"
        alt=""
        class="sm:h-[45vw] sm:mx-auto xl:h-[33vw]"
      />
      <div
        id="paper"
        class="bg-[url('/paper.png')] sm:mt-10 md:mt-0 bg-no-repeat sm:bg-[50%] xl:bg-[center_top] lg:bg-cover xl:bg-cover"
      >
        <div
          class="grid sm:w-[98%] xl:w-11/12 sm:text-center lg:text-left xl:mt-7"
        >
          <span class="font-['Ubuntu'] text-base text-[#673e2c] font-[300]"
            >Inspired by tales of their grandfather's pioneering days, the
            protagonist decides to pack their bags and leave the hustle and
            bustle of big city life for the frontier in Olive Town.
          </span>
          <span
            class="sm:mt-7 md:mt-4 xl:mt-7 font-['Ubuntu'] text-base text-[#673e2c] font-[300]"
            >When they arrive, they run into Victor, the town's mayor and their
            grandfather's old friend. He brings them to the old farm, which has
            been reclaimed by nature over the years. Determined to breathe life
            back into their grandfather's dream and follow in his footsteps, the
            protagonist rolls up their sleeves and gets to work.
          </span>
          <span
            class="sm:mt-7 md:mt-4 xl:mt-7 font-['Ubuntu'] text-base text-[#673e2c] font-[300]"
            ><span class="font-bold italic">Olive Town</span> —which is just a
            stone's throw away from the farm—is a port town built on the tip of
            a peninsula. It might be a quiet little town, but it is home to a
            whole host of unique characters. And while the townsfolk get by well
            enough in this picturesque seaside locale, a little more tourism
            never hurt anyone...
          </span>
        </div>
      </div>
    </div>
  </div>
  <div
    class="green-zigzag bg-[#ffe8be] 2xl:mx-auto 2xl:w-[1600px]"
    id="featurestrg"
  >
    &nbsp;
  </div>
</template>

<style scoped>
.green-zigzag {
  background-image: linear-gradient(44deg, #a8db90 52%, transparent 52%),
    linear-gradient(317deg, #a8db90 52%, transparent 52%);
}

.green-zigzag {
  background-size: 30px 30px;
  height: 30px;
}

@media (min-width: 640px) {
  #paper {
    height: 460px;
    padding: 40px;
  }
}

@media (min-width: 768px) {
  #paper {
    width: 700px;
    height: 380px;
  }
}

@media (min-width: 1024px) {
  #paper {
    width: 500px;
    height: 580px;
    padding: 55px;
  }
}

@media (min-width: 1280px) {
  #paper {
    width: 570px;
    height: 650px;
  }
}
</style>
