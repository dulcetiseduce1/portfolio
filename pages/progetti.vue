<template>
  <div
    class="w-full h-screen bg-local bg-cover"
    style="
      background-image: url('https://images.unsplash.com/photo-1619252584172-a83a949b6efd?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1074&q=80');
    "
  >
  <div class="grid">
      <div class="p-6 text-2xl font-semibold md:text-4xl font-Syne">
        <NuxtLink to="/">
        <p class="inline ">Informazioni</p>
        </NuxtLink>
          <p class="inline pl-4 underline">Progetti</p>
        
      </div>
    <div class="grid text-4xl font-bold pt-9 font-Syne place-items-center">
      <NuxtLink to="https://social-test-podas.vercel.app/">
      <p class="">Podas</p>
      </NuxtLink>
      <NuxtLink to="https://github.com/dulcetiseduce1">
      <p class="">Github</p>
      </NuxtLink>
    </div>
  </div>
  </div>
</template>
