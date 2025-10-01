<script setup>
// import { FastForwardIcon } from '@heroicons/vue/24/solid'

</script>

<template>
  <div>
    <div class="min-h-dvh relative">
      <!-- <div class="absolute inset-0 m-auto w-fit h-fit animate-pulse text-center p-10">
        <h1 class="text-6xl font-bold text-red-500">Work In-progress!</h1>
      <p class="text-center mt-3">Stay Tuned!</p>
    </div> -->
      <div class="flex flex-col items-center absolute bottom-0 left-1/2 -translate-x-1/2">
        <img src="/public/fast-forward.gif" alt=""
          class="w-20 h-20 object-cover opacity-60 rotate-90 absolute top-[3rem]" />
        <img src="/public/jose-marie.jpeg" alt="" class="w-96 h-96 object-cover opacity-60" />
      </div>
    </div>
    <div class="min-h-dvh bg-black grid place-items-center">
      <h1 class="text-6xl font-bold text-white">Coming Soon!</h1>
    </div>
  </div>
</template>

<style scoped>
@keyframes fadeDown {
  0% {
    opacity: 0;
    transform: translateY(-5px);
  }

  50% {
    opacity: 1;
    transform: translateY(0);
  }

  100% {
    opacity: 0;
    transform: translateY(5px);
  }
}

.animate-fadeDown {
  animation: fadeDown 1.5s infinite;
}
</style>
