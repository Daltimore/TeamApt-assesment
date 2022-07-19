<template>
  <main
    class="min-h-screen relative bg-[url('https://res.cloudinary.com/dtq7cistx/image/upload/v1658191613/bg-img_oliben.svg')] bg-no-repeat bg-cover"
  >
    <div>
      <navbar></navbar>
      <div class="absolute top-[125px] left-2/4 -translate-x-2/4 w-4/5">
        <img src="~/assets/svg-icons/diff-stars.svg" alt="" />
      </div>
    </div>
    <div class="flex justify-center flex-col">
      <div class="leading-[69px] hidden md:block pb-6">
        <h1
          class="text-white font-light text-3xl md:text-[70px] text-center pb-5 animate-1"
        >
          Unlock to
        </h1>
        <h1
          class="text-white font-bold text-4xl md:text-[70px] text-center animate-2"
        >
          Power your dreams!
        </h1>
      </div>
      <div class="block md:hidden">
        <h1
          class="px-4 text-white font-light text-4xl md:text-[70px] text-center animate-1"
        >
          Unlock to <b class="font-bold">Power your dreams!</b>
        </h1>
      </div>

      <div class="font-normal inter my-5 px-6 md:px-0 pb-4">
        <div
          class="hidden md:block text-white text-center text-[20px] md:text-[29px] leading-8"
        >
          <p class="font-light animate-3">Stand a chance to win</p>
          <p class="font-light animate-4">
            <b class="font-bold">₦3,000,000</b> everyday for the next 5 days
          </p>
        </div>
        <div
          class="block md:hidden text-white text-center text-[20px] md:text-[29px] leading-7"
        >
          <p class="font-light animate-3">
            Stand a chance to win
            <span class="font-light animate-4">
              <b class="font-bold">₦3,000,000</b> everyday for the next 5 days
            </span>
          </p>
        </div>
      </div>
      <section class="px-6 md:px-0">
        <div class="how_to_play w-full md:w-[480px] mx-auto p-[27px] mt-[4px]">
          <header>
            <p class="text-white text-center inter font-bold pb-3.5">
              🚀 &nbsp; How To Play
            </p>
          </header>
          <ol class="leading-8 text-white inter font-normal pl-1.5 list-inside">
            <li class="text-sm md:text-base">
              Guess the right combination of numbers
            </li>
            <li class="text-sm md:text-base">
              Win <b class="font-semibold">₦3,000,000</b> instantly
            </li>
          </ol>
          <p class="leading-5 text-sm text-white pt-2">
            Sounds unbelievable? Well, guess right & see for yourself!
          </p>
          <div
            class="bg-black/30 rounded-[10px] py-2.5 md:py-3.5 px-[10px] my-[26px] flex"
          >
            <span class="mt-0.5 mr-2">
              <img src="~/assets/svg-icons/bulb.svg" class="w-12" alt="" />
            </span>
            <p class="text-white text-xs font-light leading-relaxed">
              Think well before you guess. You have only 2 attempts per day and
              even after you win, you can come back the next day to try for
              another jackpot!
            </p>
          </div>
        </div>
      </section>
      <div class="flex justify-center items-center mt-[44px] mb-[256px]">
        <button
          class="relative w-[225px] bg-[#ECAB03] text-white flex flex-row text-center justify-center h-[56px] rounded items-center font-semibold animate-btn focus:outline-none"
        >
          <p class="-ml-5">Play The Game</p>
          <span class="absolute right-3.5">
            <img src="~/assets/svg-icons/right-icon.svg" alt="" />
          </span>
        </button>
      </div>
    </div>
    <div class="animation-box">
      <img
        src="~/assets/svg-icons/rotate-star.svg"
        alt="rotating light effect"
        class="rotating-star"
      />
      <img
        src="~/assets/svg-icons/coin-pot.svg"
        alt="coin-pot-illustration"
        class="coin-pot animate-coin-pot"
      />
      <div class="coins">
        <img
          id="coin-1"
          src="~/assets/svg-icons/coin-left.svg"
          alt="coin-illustration"
          class="coins__left-coin"
        />
        <img
          id="coin-2"
          src="~/assets/svg-icons/coin-right.svg"
          alt="coin-illustration"
          class="coins__right-coin"
        />
      </div>
    </div>
    <div class="night-stars-box">
      <img
        src="~/assets/svg-icons/star-one.svg"
        alt="star-illustration"
        class="night-stars night-star-one"
      />
      <img
        src="~/assets/svg-icons/star-two.svg"
        alt="star-illustration"
        class="night-stars night-star-two"
      />
      <img
        src="~/assets/svg-icons/star-three.svg"
        alt="star-illustration"
        class="night-stars night-star-three"
      />
      <img
        src="~/assets/svg-icons/star-four.svg"
        alt="star-illustration"
        class="night-stars night-star-four"
      />
      <img
        src="~/assets/svg-icons/star-five.svg"
        alt="star-illustration"
        class="night-stars night-star-five"
      />
    </div>
  </main>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>
