<template>
  <div
    class="flex bg-white nav-shadow z-[1000] fixed top-0 w-full shadow-xl py-4 flex-row justify-center items-center"
  >
    <div class="flex flex-row justify-between item-center w-full max-w-6xl">
      <img class="w-[171px] h-[39px]" src="../static/logo.png" alt="logo" />
      <nav
        class="text-sm font-[600] gap-14 text-[#666666] flex flex-row justify-center item-center"
      >
        <div class="flex gap-12 flex-row justify-center items-center">
          <a href="#" class="hover:text-black">Changelog</a>
          <a href="#" class="hover:text-black">Testimonials</a>
          <a href="#" class="hover:text-black">License Manager</a>
          <a href="#" class="hover:text-black">FAQ</a>
          <a href="#" class="text-primary">Log in to Cloud</a>
        </div>
        <button class="bg-primary px-[25px] py-[11px] rounded-full text-white">
          Buy now
        </button>
      </nav>
    </div>
  </div>
</template>

<style>
.nav-shadow {
  box-shadow: 0 14px 20px -8px #0e0c1b0d;
}
</style>
