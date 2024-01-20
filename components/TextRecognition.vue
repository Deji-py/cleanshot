<template>
  <section
    class="w-full flex gap-20 flex-row justify-between items-center max-w-6xl"
  >
    <div class="left flex-1 flex flex-col gap-5 justify-start items-start">
      <h1 class="text-[48px] font-bold">Text recognition</h1>
      <p class="text-xl font-[400]">
        Need to create a beautiful social media post? It's now easier than ever
        to make your screenshots pop with just a few clicks, right inside
        CleanShot!
      </p>

      <div
        class="highlights font-bold flex flex-col justify-start items-start gap-3"
      >
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-float.7b035edf.svg" alt="" />
          </div>
          <div class="highlight-name">Easily copy non-selectable text</div>
        </div>
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-notifications.9a675425.svg" alt="" />
          </div>
          <div class="highlight-name">OCR technology</div>
        </div>
        <div class="highlight">
          <div class="highlight-icon">
            <img src="../static/20-bolt.af9f971b.svg" alt="" />
          </div>
          <div class="highlight-name">Super fast on-device recognition</div>
        </div>
      </div>
    </div>
    <div class="w-[55%]">
      <video class="video -qao" playsinline muted loop autoplay>
        <source
          src="https://cleanshot.com/_nuxt/ocr.dca73a41.mp4"
          type="video/mp4"
        />
      </video>
    </div>
  </section>
</template>
