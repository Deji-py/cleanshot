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
          src="https://cleanshot.com/_nuxt/scrolling.ea3a6778.mp4"
          type="video/mp4"
        />
      </video>
    </div>

    <div class="left flex-1 flex flex-col gap-5 justify-start items-start">
      <h1 class="text-[48px] font-bold">Scrolling capture</h1>
      <p class="text-xl font-[400]">
        Need to capture something that doesn't fit on your screen? Maybe you
        want to save a chat history or a larger chunk of code? We got you
        covered!
      </p>

      <div class="flex flex-col justify-start items-center gap-3">
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-scroll.50d2c5a0.svg" alt="" />
          </div>
          <div class="highlight-name">
            Self destruct control&nbsp;<a href="/pricing" class=""></a>
          </div>
        </div>
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-apps.0c42c6f4.svg" alt="" />
          </div>
          <div class="highlight-name">
            Self destruct control&nbsp;<a href="/pricing" class=""></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
