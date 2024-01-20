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
          src="https://cleanshot.com/_nuxt/qao.547f0213.mp4"
          type="video/mp4"
        />
      </video>
    </div>
    <div class="left flex-1 flex flex-col gap-5 justify-start items-start">
      <h1 class="text-[48px] font-bold">Annotate</h1>
      <p class="text-xl font-[400]">
        In a matter of seconds highlight important parts of your screenshot with
        our annotation tool. Loved by our users, it beats any other annotation
        app.
      </p>
      <div>Indicators Here</div>
    </div>
  </section>
</template>
