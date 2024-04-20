<template>
  <div class="my-10 px-5 pt-5 pb-10">
    <h1 class="font-bold text-2xl md:text-4xl mb-6">
      Nos contributeurs vedettes
    </h1>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 lg:gap-10">
      <div v-for="i in 4" :key="i" class="relative rounded-md my-6">
        <img
          class="object-cover h-28 w-full rounded-md"
          src="assets/makifaa-shoot.jpg"
          alt="couverture contributeur"
        />

        <img
          class="border-4 border-white rounded-full w-14 h-14 absolute left-4 bottom-[-40px] object-cover object-center"
          src="assets/doris.jpg"
          alt=""
        />
        <div class="absolute left-20 text-xs mt-1">
          <nuxt-link class="font-bold" to="/u/smartboy">@Smartboy</nuxt-link>
          <p>233 Médias</p>
        </div>
      </div>
    </div>
  </div>
</template>
