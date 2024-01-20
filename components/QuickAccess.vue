<template>
  <section
    class="w-full flex gap-20 flex-row justify-center items-center max-w-6xl"
  >
    <div class="left flex-1 flex flex-col gap-5 justify-start items-start">
      <h1 class="text-[48px] font-bold">Quick Access</h1>
      <p class="text-xl font-[400]">
        Our overlay makes sharing a breeze. Instantly save, copy or drag & drop
        screenshots or screen recordings to other apps. Whatever your workflow
        looks like, it's going to fit.
      </p>
      <a
        href="#"
        class="flex gap-1 justify-start items-center text-sm text-primary font-bold"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
        >
          <path fill="currentColor" d="M8 5.14v14l11-7z" />
        </svg>

        Watch the Video
      </a>
      <div
        class="bg-gray-100 p-5 gap-5 rounded-3xl flex flex-row justify-start items-center"
      >
        <img class="w-10 rounded-xl" src="../static/tyler.webp" alt="" />
        <div class="text-sm">
          <p>
            The essential swiss army knife for screenshots, markups, and GIFs.
            Every Mac owner needs this.
          </p>
          <div class="pt-2">
            <strong>
              <span class="hover:text-primary"> Tyler Tringas, </span> Founder
              at Earnest Capital
            </strong>
          </div>
        </div>
      </div>
    </div>
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
  </section>
</template>
