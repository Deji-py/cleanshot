<template>
  <section class="changes py-24 w-full max-w-6xl">
    <div
      class="w-full flex flex-row justify-start items-center pl-24 bg-[#f6f6f6] bg-right-0 bg-repeat-y rounded-3xl"
    >
      <div>
        <div class="text-[32px] font-light text-gray-700">
          It feels like 7 apps in one.
        </div>
        <div class="text text-[48px] font-bold text-black mt-6">
          CleanShot X provides over
          <a href="/features" class="text-blue-500 hover:underline">
            <span class="blue"> 50&nbsp;features </span>
          </a>
          making it the ultimate screen capturing tool.
        </div>
        <div class="text-[20px] flex mt-12">
          <a
            href="/features"
            class="-first mr-12 gap-2 flex items-center text-blue-500 font-bold transition duration-100 ease-in hover:text-blue-900"
          >
            Check all features
            <svg
              width="20"
              height="20"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
              class="arrow"
              alt=""
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M7.3 4.3a1 1 0 011.4 0l5 5c.4.4.4 1 0 1.4l-5 5a1 1 0 01-1.4-1.4l4.3-4.3-4.3-4.3a1 1 0 010-1.4z"
              ></path>
            </svg>
          </a>
          <a
            href="/changelog"
            class="text-blue-500 flex gap-2 items-center font-bold transition duration-100 ease-in hover:text-blue-900"
          >
            What's new?
            <svg
              width="20"
              height="20"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
              class="arrow"
              alt=""
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M7.3 4.3a1 1 0 011.4 0l5 5c.4.4.4 1 0 1.4l-5 5a1 1 0 01-1.4-1.4l4.3-4.3-4.3-4.3a1 1 0 010-1.4z"
              ></path>
            </svg>
          </a>
        </div>
      </div>
      <!--  -->
      <img src="../static/feature-img.png" alt="" />
    </div>
  </section>
</template>

<style>
/* Add custom styles */
.blue {
  color: #0669ff;
  cursor: pointer;
  transition: all 0.15s ease;
}

.blue:hover {
  text-decoration: underline;
}

/* Add more custom styles as needed */
</style>
