<template>
  <div class="space-y-6">
    <NuxtImg src="/avatar.jpg" alt="Ruslan Ubaydullayev"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px" placeholder format="jpg" />
    <h1 class="text-xl font-bold tracking-tight text-primary-500">
      👋🏻
    </h1>
    <p class="text-gray-900 dark:text-gray-400">
      I'm Ruslan, I work as a software engineer from
      Tashkent, Uzbekistan. I specialize in building web applications and sites
      using Javascript, Vue, Nuxtjs. I've carved out my own little
      nook on the internet to share my silly experiments, nifty projects, and
      thoughts (mostly about tech and design).
    </p>
    <p class="text-gray-900 dark:text-gray-400">
      By day, I'm a Frontend Developer at
      <a href="https://business.ipakyulibank.uz" target="_blank" class="underline">ipakyulibank.uz</a>, and
      by night (and weekends), I'm busy tinkering with some random tool or app
      that I am building.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "activus.uz | portfolio",
  description:
    "I'm Ruslan, your friendly neighborhood software, product engineer and designer from Tashkent, Uzbekistan. I specialize in building web applications and sites using Javascript, Vue.",
});
</script>
