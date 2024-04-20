<template>
  <div class="my-10 bg-slate-100 px-5 pt-5 pb-10">
    <h1 class="font-bold text-2xl md:text-4xl mb-6">
      Classés par catégories
    </h1>
    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-2">
      <div v-for="i in 12" :key="i" class="relative rounded-sm">
        <img
          class="object-cover h-20 w-full rounded-sm"
          src="assets/hero-img.jpg"
          alt="couverture categorie"
        />
        <div
          class="absolute rounded-md inset-0 bg-black opacity-0 hover:opacity-70 z-10 cursor-pointer transition-opacity duration-300 ease-in-out"
        >
          <p class="z-20 text-white text-md mt-5 ml-5">Education</p>
        </div>
      </div>
    </div>
  </div>
</template>
