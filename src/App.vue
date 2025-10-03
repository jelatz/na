<script setup>
</script>

<template>
  <div class="min-h-dvh bg-black bg-[url('/public/bg.png')] bg-top bg-cover bg-no-repeat relative">
    <!-- Hero Section -->
    <div class="flex flex-col items-center pt-20 space-y-6 relative z-10">
      <img src="/public/logo.png" alt="logo" class="w-[20rem] md:w-[30rem]" />
      <img src="/public/topic.png" alt="topic" class="w-[30rem] md:w-[50rem]" />
    </div>

    <!-- Church Decoration -->
    <img src="/public/church.png" alt="church"
      class="w-[20rem] md:w-[40rem] opacity-20 absolute bottom-2 right-4 md:right-60" />

    <!-- Content Section -->
    <div class="flex flex-col justify-start items-center  space-y-10 relative z-10 px-6">
      <div>
        <!-- Block 1 -->
        <div class="text-white max-w-2xl my-5">
          <p class="font-extrabold text-2xl mb-3">From Pain to Purpose</p>
          <ul class="list-disc list-inside space-y-2 text-lg">
            <li>Butch A. - Redemtorist HG</li>
            <li>Harold G. - Bliss HG</li>
            <li>Jepoy E. - Bohol HG</li>
            <li>Nyang S. - Kufa Habagatan HG</li>
          </ul>
        </div>

        <!-- Block 2 -->
        <div class="text-white max-w-2xl my-5">
          <p class="font-extrabold text-2xl mb-3">The key to freedom is in the steps.</p>
          <ul class="list-disc list-inside space-y-2 text-lg">
            <li>Khim K. - </li>
            <li>Jeffrey G. - Sleeping Dragons HG (Pardo)</li>
            <li>Frankie T. - Isla HG</li>
          </ul>
        </div>

        <!-- Block 3 -->
        <div class="text-white max-w-2xl my-5">
          <p class="font-extrabold text-2xl mb-3">Nothing changes if nothing changes</p>
          <ul class="list-disc list-inside space-y-2 text-lg">
            <li>Renniel B. - Isla HG</li>
            <li>Stephen T. - Sleeping Dragon HG (Pardo)</li>
            <li>Jerome C. - Bacayan HG</li>
          </ul>
        </div>
      </div>
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
