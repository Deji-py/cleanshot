<template>
  <section class="w-full max-w-6xl text-black h-full 0">
    <div class="w-full px-8 pb-8 border-[1px] rounded-2xl">
      <div class="flex py-4 flex-row justify-center items-center gap-10">
        <button
          class="p-2 px-6 hover:bg-black hover:text-white bg-white rounded-full border-[0.2px]"
          v-for="(item, index) in tabs"
          :key="index"
        >
          {{ item }}
        </button>
      </div>
      <div
        class="bg-red-50 flex flex-col justify-center items-center rounded-2xl h-[30rem]"
      >
        <p>Hello</p>
      </div>
    </div>
  </section>
</template>

<script>
import { ref } from "vue";
import Features from "../components/Features.vue";
export default {
  setup() {
    const tabs = ref([
      "Embeds",
      "Files",
      "Forms",
      "SubTasks",
      "Buttons",
      "Text",
    ]);

    return {
      tabs,
    };
  },
};
</script>
