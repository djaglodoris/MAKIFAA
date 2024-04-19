import Nav from './Components/Nav.vue';
<template>
  <div class="max-w-screen-2xl mx-auto">
    <!-- NAV -->
    <div class="flex items-center justify-between pr-8">
      <div class="flex items-center gap-10">
        <nuxt-link to="/">
          <img
            class="h-20 w-40 object-cover cursor-pointer"
            src="assets/logo - Makifaa 2.svg"
            alt="logo makifaa"
          />
        </nuxt-link>
        <ul class="flex items-center gap-5 font-semibold">
          <li class="flex gap-1 cursor-pointer">
            <nuxt-link to="">Images</nuxt-link>
            <Icon
              class="self-end"
              name="material-symbols:keyboard-arrow-down-rounded"
            />
          </li>
          <li class="flex gap-1 cursor-pointer">
            <nuxt-link to="">Business</nuxt-link>
            <Icon
              class="self-end"
              name="material-symbols:keyboard-arrow-down-rounded"
            />
          </li>
          <li class="flex gap-1 cursor-pointer">
            <nuxt-link to="">Pricing</nuxt-link>
          </li>
        </ul>
      </div>
      <div>
        <ul class="flex gap-10 items-center font-semibold">
          <li class="flex gap-1 cursor-pointer">
            <p class="uppercase">fr</p>
            <Icon
              class="self-end"
              name="material-symbols:keyboard-arrow-down-rounded"
            />
          </li>
          <li class="flex gap-1 cursor-pointer">
            <p>Aide</p>
          </li>
          <li class="flex gap-1 cursor-pointer">
            <nuxt-link
              to="/login"
              class="bg-[#c07313] text-white px-5 py-2 rounded-md"
            >
              Connexion
            </nuxt-link>
          </li>
        </ul>
      </div>
    </div>
    <!-- HERO -->
    <div class="relative h-[75vh]">
      <img
        class="absolute h-full w-full object-cover"
        src="assets/hero-img.jpg"
        alt="hero image"
      />
      <div class="absolute inset-0 bg-black opacity-80 h-full z-20"></div>
      <div
        class="absolute text-white flex flex-col gap-6 h-full w-full justify-center items-center z-40"
      >
        <h1 class="text-6xl font-bold text-center max-w-4xl">
          Besoin de médias africains sur mesure pour vos projets ?
        </h1>
        <p class="text-base">
          Accédez à une bibliothèque en constante évolution remplie d'images
          typiquement africaines
        </p>
        <div class="flex items-center mt-10">
          <!-- <button class="py-4 px-5 bg-[#143e4e] text-white rounded-l-md">
            Images
          </button> -->
          <input
            type="search"
            placeholder="Rechercher les meilleures images pour votre projet créatif  "
            class="w-96 py-4 px-4 rounded-l-xl text-black focus:outline-none text-lg"
          />
          <button
            class="flex items-center bg-[#c07313] text-white px-6 py-4 rounded-r-xl font-semibold text-lg"
          >
            <Icon class="w-6 h-6" name="material-symbols-light:search" />
            Rechercher
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
