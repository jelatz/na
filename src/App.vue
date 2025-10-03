<script setup>
</script>

<template>
  <div class="min-h-dvh bg-black bg-[url('/public/bg.png')] bg-top bg-cover object-cover bg-no-repeat relative">
    <!-- Hero Section -->
    <div class="flex flex-col items-center pt-20 space-y-6 relative z-10 px-5 sm:px-0">
      <img src="/logo.webp" loading="lazy" alt="logo" class="w-[20rem] md:w-[30rem]" />
      <img src="/topic.webp" loading="lazy" alt="topic" class="w-[30rem] md:w-[50rem]" />
    </div>


    <!-- Program Flow -->
    <div class="flex flex-col justify-start items-center space-y-10 relative z-10 px-6 py-10">
      <!-- Church Decoration -->
      <img src="/church.webp" alt="church"
        class="w-[20rem] md:w-[40rem] opacity-20 fixed bottom-2 right-4 md:right-60 z-0" />

      <div class="text-white max-w-xl w-full">
        <h1 class="text-3xl text-white font-extrabold mb-6 text-center">Program Flow</h1>

        <ul class="space-y-6 text-lg">
          <!-- Registration -->
          <li>
            <p class="font-bold">07:30 AM - 08:30 AM — Registration</p>
            <p class="ml-5 italic text-sm">(08:00 AM - 08:30 AM): Ralph speech on how Pardo Homegroup started
            </p>
          </li>

          <!-- 1st Meeting -->
          <li>
            <p class="font-bold">08:30 AM - 10:00 AM — 1st Meeting: From Pain to Purpose</p>
            <ul class="list-disc list-inside ml-6 text-sm">
              <li>Butch A. - Redemtorist HG</li>
              <li>Harold G. - Bliss HG</li>
              <li>Nyang S. - Kuta Habagatan HG</li>
              <li>Jepoy E. - Bohol HG</li>
            </ul>
          </li>

          <!-- Break -->
          <li>
            <p class="font-bold">10:00 AM - 10:15 AM — Break</p>
          </li>

          <!-- 2nd Meeting -->
          <li>
            <p class="font-bold">10:15 AM - 11:45 AM — 2nd Meeting: The key to freedom is in the steps</p>
            <ul class="list-disc list-inside ml-6 text-sm">
              <li>Khim K. - LaBang Subangdaku HG</li>
              <li>Jeffrey G. - Sleeping Dragons HG (Pardo)</li>
              <li>Frankie T. - Isla HG</li>
            </ul>
          </li>

          <!-- Trivia -->
          <li>
            <p class="font-bold">11:45 AM - 12:00 PM — Trivia & Games</p>
          </li>

          <!-- Lunch -->
          <li>
            <p class="font-bold">12:00 PM - 01:00 PM — Lunch</p>
          </li>

          <!-- 3rd Meeting -->
          <li>
            <p class="font-bold">01:00 PM - 02:30 PM — 3rd Meeting: Nothing changes if nothing changes</p>
            <ul class="list-disc list-inside ml-6 text-sm">
              <li>Renniel B. - Isla HG</li>
              <li>Stephen T. - Sleeping Dragon HG (Pardo)</li>
              <li>Jerome C. - Bacayan HG</li>
            </ul>
          </li>

          <!-- Break -->
          <li>
            <p class="font-bold">02:30 PM - 02:45 PM — Break</p>
          </li>

          <!-- Bidding -->
          <li>
            <p class="font-bold">02:45 PM - 03:15 PM — Bidding & (Trivia & Games)</p>
          </li>

          <!-- Countdown -->
          <li>
            <p class="font-bold">03:15 PM - 05:00 PM — Countdown</p>
          </li>
        </ul>
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
