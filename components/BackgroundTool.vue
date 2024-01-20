<template>
  <section
    class="w-full py-40 flex gap-20 flex-row justify-between items-center max-w-6xl"
  >
    <div class="w-[55%]">
      <video class="video -qao" playsinline muted loop autoplay>
        <source
          src="https://cleanshot.com/_nuxt/bgtool.611527af.mp4"
          type="video/mp4"
        />
      </video>
    </div>
    <div class="left flex-1 flex flex-col gap-5 justify-start items-start">
      <h1 class="text-[48px] font-bold">Background tool</h1>
      <p class="text-xl font-[400]">
        Need to create a beautiful social media post? It's now easier than ever
        to make your screenshots pop with just a few clicks, right inside
        CleanShot!
      </p>

      <div
        class="highlights font-bold flex flex-col justify-start items-start gap-2"
      >
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-heart.bc3bdea7.svg" alt="" />
          </div>
          <div class="highlight-name">Perfect for social media</div>
        </div>
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-clutter.6e8535c4.svg" alt="" />
          </div>
          <div class="highlight-name">10 beautiful backgrounds included</div>
        </div>
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-float.7b035edf.svg" alt="" />
          </div>
          <div class="highlight-name">Add your own background</div>
        </div>
      </div>
    </div>
  </section>
</template>
