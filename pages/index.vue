<template>
  <div class="bg-slate-100 h-full w-full">
    <header class="relative ">
      <nav class="flex justify-between fixed top-0 left-0 right-0 bg-black text-white font-bold px-[3%] py-2 h-[5%] ">
        <NuxtLink to="#">URLShortify</NuxtLink>
        <div class=" ">
          <NuxtLink to="/login" class="mx-4">Se connecter</NuxtLink>
          <NuxtLink to="/register">S'inscrire</NuxtLink>
        </div>
      </nav>
    </header>
      <div class="text-black text-center pt-[20%]">
        <p>Hello Nuxt! 🚀👩‍🚀</p>
      </div>
    
  </div>
</template>

<script lang="ts" setup>

</script>

<style>

</style>