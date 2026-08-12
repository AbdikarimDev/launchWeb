<template>
  <div class="flex justify-around items-center text-white my-4">
    <div class="flex gap-10 justify-between items-center">
      <!-- logo -->
      <div class="flex  gap-2">
        <img src="../../public/favicon.svg" alt="" />
        <h1 class="font-bold text-[18px]">Launch UI</h1>
      </div>
      <!-- navigations -->
      <div class="flex gap-10">
        <a href="home" class="font-[400] text-[14px]">Getting started</a>
        <a href="components" class="font-[400] text-[14px]">Components</a>
        <a href="documentation" class="font-[400] text-[14px]">Documentation</a>
        <a href="QA" class="font-[400] text-[14px]">QA</a>
      </div>
    </div>
    <!-- Buttons -->
     <div>
        <button class="font-[500] text-[14px] bg-black px-4 py-3 ">Sign in</button>
        <button class="font-[500] text-[14px] text-black bg-white px-4 py-3 rounded-[8px]">Get started</button>
     </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped></style>
