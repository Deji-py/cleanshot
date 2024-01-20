<template>
  <section
    class="w-full py-40 flex gap-20 flex-row justify-center items-center max-w-6xl"
  >
    <div class="w-[55%]">
      <video
        class="video -qao"
        playsinline
        muted
        loop
        autoplay
        poster="../static/quest-video-cover.webp"
      >
        <source
          src="https://cleanshot.com/_nuxt/floating.d7645abb.mp4"
          type="video/mp4"
        />
      </video>
    </div>

    <div class="left flex-1 flex flex-col gap-5 justify-start items-start">
      <h1 class="text-[48px] font-bold">Pin screenshots</h1>
      <p class="text-xl font-[400]">
        Keep a reference of anything you need always visible. It will float
        above all windows.
      </p>

      <div
        class="highlights flex flex-col justify-start items-start gap-3"
        data-v-1e3615d1=""
      >
        <div class="highlight" data-v-1e3615d1="">
          <div class="highlight-icon" data-v-1e3615d1="">
            <img
              src="../static/20-opacity.384373cf.svg"
              alt=""
              data-v-1e3615d1=""
            />
          </div>
          <div class="highlight-name" data-v-1e3615d1="">
            Adjust size &amp; opacity
          </div>
        </div>
        <div class="highlight" data-v-1e3615d1="">
          <div class="highlight-icon" data-v-1e3615d1="">
            <img
              src="../static/20-float.7b035edf.svg"
              alt=""
              data-v-1e3615d1=""
            />
          </div>
          <div class="highlight-name" data-v-1e3615d1="">Always on top</div>
        </div>
      </div>
    </div>
  </section>
</template>
