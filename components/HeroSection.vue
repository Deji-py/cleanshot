<template>
  <section class="pt-20 w-full flex flex-row justify-center items-center">
    <div
      class="flex w-full py-24 flex-row justify-center items-center max-w-6xl"
    >
      <h1 class="text-6xl leading-tight w-[65%] font-bold">
        <span class="text-gradient"> AI-Powered </span> customer onboarding
        tours for SaaS companies
      </h1>
      <div class="flex-1">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat, quos
          dolore inventore eligendi dignissimos natus exercitationem atque
        </p>

        <div class="flex pt-8 flex-row justify-start items-center gap-5">
          <button
            class="bg-primary font-semibold text-white w-[146px] py-3.5 rounded-full h-[56]"
          >
            Buy now
          </button>
          <button
            class="bg-gray-100 hover:bg-gray-200 flex flex-row justify-center items-center gap-2 text-text w-[200px] py-3.5 rounded-full h-[56]"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
            >
              <path fill="currentColor" d="M8 5.14v14l11-7z" />
            </svg>
            <p class="font-semibold">How it works</p>
          </button>
        </div>
        <p class="text-gray-800 mt-5">* No credit card required</p>
      </div>
    </div>
  </section>
</template>

<style>
.text-gradient {
  background: linear-gradient(
    93deg,
    #0669ff 45.55%,
    #0669ff 53.19%,
    #9ec5ff 55.18%,
    #0669ff 62.74%,
    #0669ff 63.35%,
    #9e9eff 85.39%,
    #095fe0 87.37%
  );
  background-clip: text;
  color: transparent;
}
</style>

<script setup></script>
