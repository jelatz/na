<script setup>
</script>

<template>
  <div class="min-h-dvh bg-black bg-[url('/public/bg.png')] bg-top bg-cover bg-no-repeat relative text-white">
    <!-- Hero Section -->
    <div class="flex flex-col items-center pt-20 space-y-6 relative z-10 px-5">
      <img src="/logo.webp" loading="lazy" alt="logo" class="w-[18rem] md:w-[28rem]" />
      <img src="/topic.webp" loading="lazy" alt="topic" class="w-[28rem] md:w-[45rem]" />
      <p class="text-center text-gray-300 text-sm italic">“From Pain to Purpose — A Journey of Change and Freedom”</p>
    </div>

    <!-- Program Flow -->
    <div class="flex flex-col items-center relative z-10 px-6 py-16">
      <!-- Decorative Church -->
      <img src="/church.webp" alt="church"
        class="w-[20rem] md:w-[35rem] opacity-15 fixed bottom-0 right-10 md:right-32 z-50 pointer-events-none" />

      <div class="max-w-2xl w-full bg-black/60 backdrop-blur-sm rounded-2xl p-8 shadow-lg border border-white/10">
        <h1 class="text-3xl font-extrabold mb-8 text-center uppercase tracking-wide">Program Flow</h1>

        <!-- Program List -->
        <ul class="space-y-8 text-sm md:text-base">
          <!-- Registration -->
          <li class="border-l-4 border-yellow-400 pl-4">
            <p class="font-bold text-yellow-300">07:30 AM – 08:30 AM — Registration & Welcome Coffee</p>
            <p class="italic ml-4 mt-1 text-gray-300">(08:00 AM – 08:30 AM): Ralph – How Pardo Homegroup Started</p>
          </li>

          <!-- 1st Meeting -->
          <li class="border-l-4 border-blue-400 pl-4">
            <p class="font-bold text-blue-300">08:30 AM – 09:30 AM — 1st Meeting: From Pain to Purpose</p>
            <ul class="list-disc list-inside ml-6 text-gray-300">
              <li>Butch A. – Redemptorist HG</li>
              <li>Harold G. – Bliss HG</li>
              <li>Nyang S. – Kuta Habagatan HG</li>
              <li>Jepoy E. – Bohol HG</li>
            </ul>
          </li>

          <!-- Break -->
          <li class="border-l-4 border-green-400 pl-4">
            <p class="font-bold text-green-300">09:30 AM – 09:45 AM — Morning Break</p>
          </li>

          <!-- Trivia & Games -->
          <li class="border-l-4 border-pink-400 pl-4">
            <p class="font-bold text-pink-300">09:45 AM – 10:45 AM — Entertainment & Games (Round 1)</p>
            <!-- <p class="ml-4 text-gray-300 italic">Interactive challenges and bonding activities</p> -->
          </li>

          <!-- 2nd Meeting -->
          <li class="border-l-4 border-purple-400 pl-4">
            <p class="font-bold text-purple-300">10:45 AM – 11:45 AM — 2nd Meeting: The Key to Freedom Is in the Steps
            </p>
            <ul class="list-disc list-inside ml-6 text-gray-300">
              <li>Khim K. – LaBang Subangdaku HG</li>
              <li>Jeffrey G. – Sleeping Dragons HG (Pardo)</li>
              <li>Frankie T. – Isla HG</li>
            </ul>
          </li>

          <!-- Lunch -->
          <li class="border-l-4 border-orange-400 pl-4">
            <p class="font-bold text-orange-300">11:45 AM – 01:00 PM — Lunch & Fellowship</p>
            <!-- <p class="ml-4 text-gray-300 italic">Share stories and laughter with fellow Homegroup members</p> -->
          </li>

          <!-- 3rd Meeting -->
          <li class="border-l-4 border-cyan-400 pl-4">
            <p class="font-bold text-cyan-300">01:00 PM – 02:00 PM — 3rd Meeting: Nothing Changes If Nothing Changes</p>
            <ul class="list-disc list-inside ml-6 text-gray-300">
              <li>Renniel B. – Bacayan HG</li>
              <li>Stephen T. – Sleeping Dragon HG (Pardo)</li>
              <li>Jerome C. – Bacayan HG</li>
            </ul>
          </li>

          <!-- Energizer -->
          <li class="border-l-4 border-emerald-400 pl-4">
            <p class="font-bold text-emerald-300">02:00 PM – 02:30 PM — Entertainment & Games (Round 2)</p>
            <!-- <p class="ml-4 text-gray-300 italic">A short activity to re-energize everyone</p> -->
          </li>

          <!-- Bidding -->
          <li class="border-l-4 border-red-400 pl-4">
            <p class="font-bold text-red-300">02:30 PM – 03:15 PM — Bidding</p>
            <!-- <p class="ml-4 text-gray-300 italic">Fun auction-style games and final trivia round</p> -->
          </li>

          <!-- Countdown -->
          <li class="border-l-4 border-yellow-500 pl-4">
            <p class="font-bold text-yellow-300">03:15 PM – 05:00 PM — Countdown & Closing Celebration</p>
            <!-- <p class="ml-4 text-gray-300 italic">Praise & Worship • Group Photos • Closing Remarks</p> -->
          </li>
        </ul>
      </div>
    </div>

    <!-- Footer -->
    <footer class="text-center text-gray-400 text-sm py-6 relative z-10">
      <p>“From pain comes purpose, from change comes freedom.”</p>
      <p class="mt-1">© 2025 Pardo Homegroup Fellowship</p>
    </footer>
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
