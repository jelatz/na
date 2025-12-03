<script setup>
</script>

<template>
  <div
    class="min-h-dvh bg-gradient-to-b from-zinc-950 via-black to-zinc-900 bg-cover bg-no-repeat relative text-amber-50">
    <!-- Overlay Background Image -->
    <div class="absolute inset-0 bg-[url('/public/bg.png')] bg-top bg-cover bg-no-repeat opacity-20"></div>

    <!-- Hero Section -->
    <div class="flex flex-col items-center pt-20 space-y-6 relative z-10 px-5 text-center">
      <img src="/logo.webp" loading="lazy" alt="logo"
        class="w-[18rem] md:w-[28rem] drop-shadow-[0_0_10px_rgba(255,191,0,0.3)]" />
      <img src="/topic.webp" loading="lazy" alt="topic"
        class="w-[28rem] md:w-[45rem] drop-shadow-[0_0_15px_rgba(255,200,100,0.4)]" />
      <p class="text-amber-300/80 text-sm italic tracking-wide">“From Pain to Purpose — A Journey of Change and Freedom”
      </p>
    </div>

    <!-- Program Flow -->
    <div class="flex flex-col items-center relative z-10 px-6 py-16">
      <!-- Decorative Church -->
      <img src="/church.webp" alt="church"
        class="w-[20rem] md:w-[35rem] opacity-10 fixed bottom-0 right-10 md:right-32 z-50 pointer-events-none" />

      <div
        class="max-w-2xl w-full bg-white/5 backdrop-blur-md rounded-2xl p-8 shadow-[0_0_25px_rgba(255,193,7,0.1)] border border-amber-400/30">
        <h1
          class="text-3xl font-extrabold mb-10 text-center uppercase tracking-widest text-amber-300 drop-shadow-[0_2px_6px_rgba(255,193,7,0.3)]">
          Program Flow
        </h1>

        <ul class="space-y-8 text-sm md:text-base text-amber-100">
          <!-- Registration -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">07:30 AM – 08:30 AM — Registration & Welcome Coffee</p>
            <p class="italic ml-4 mt-1 text-amber-400/60">(08:00 AM – 08:30 AM): Ralph — How Pardo Homegroup Started</p>
          </li>

          <!-- 1st Meeting -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">08:30 AM – 09:30 AM — 1st Meeting: From Pain to Purpose</p>
            <ul class="list-disc list-inside ml-6 text-amber-100/80">
              <li>Butch A. — Redemptorist HG</li>
              <li>Harold G. — Bliss HG</li>
              <li>Nyang S. — Kuta Habagatan HG</li>
              <li>Jepoy E. — Bohol HG</li>
            </ul>
          </li>

          <!-- Break -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">09:30 AM – 09:45 AM — Morning Break</p>
          </li>

          <!-- Trivia & Games -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">09:45 AM – 10:45 AM — Entertainment & Games (Round 1)</p>
            <!-- <p class="ml-4 text-amber-400/60 italic">Interactive team activities and bonding moments</p> -->
          </li>

          <!-- 2nd Meeting -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">10:45 AM – 11:45 AM — 2nd Meeting: The Key to Freedom Is in the Steps
            </p>
            <ul class="list-disc list-inside ml-6 text-amber-100/80">
              <li>Jheck Y.</li>
              <li>Jeffrey G. — Sleeping Dragons HG (Pardo)</li>
              <li>Frankie T. — Isla HG</li>
            </ul>
          </li>

          <!-- Lunch -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">11:45 AM – 01:00 PM — Lunch & Fellowship</p>
            <!-- <p class="ml-4 text-amber-400/60 italic">Enjoy a meal and connect with fellow Homegroup members</p> -->
          </li>

          <!-- 3rd Meeting -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">01:00 PM – 02:00 PM — 3rd Meeting: Nothing Changes If Nothing Changes
            </p>
            <ul class="list-disc list-inside ml-6 text-amber-100/80">
              <li>Renniel B. — Bacayan HG</li>
              <li>Stephen T. — Sleeping Dragon HG (Pardo)</li>
              <li>Jerome C. — Bacayan HG</li>
            </ul>
          </li>

          <!-- Energizer -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">02:00 PM – 02:30 PM — Entertainment & Games (Round 2)</p>
            <!-- <p class="ml-4 text-amber-400/60 italic">A short, lively group activity to re-energize everyone</p> -->
          </li>

          <!-- Bidding -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">02:30 PM – 03:15 PM — Bidding</p>
            <!-- <p class="ml-4 text-amber-400/60 italic">Fun auction-style games and final trivia round</p> -->
          </li>

          <!-- Countdown -->
          <li class="border-l-4 border-amber-400/70 pl-4">
            <p class="font-bold text-amber-300">03:15 PM – 05:00 PM — Countdown & Closing Celebration</p>
            <!-- <p class="ml-4 text-amber-400/60 italic">Praise & Worship • Group Photos • Closing Remarks</p> -->
          </li>
        </ul>
      </div>
    </div>

    <!-- Footer -->
    <footer class="text-center text-amber-400/80 text-sm py-8 relative z-10">
      <p class="italic">“From pain comes purpose, from change comes freedom.”</p>
      <p class="mt-1 text-amber-500/50 text-xs">© 2025 Pardo Homegroup Fellowship</p>
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
