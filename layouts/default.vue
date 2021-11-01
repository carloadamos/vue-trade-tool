<template>
  <div class="flex flex-col md:flex-row bg-gray-900">
    <div class="flex-col w-full md:w-64 px-4 text-gray-200">
      <div class="flex w-full flex-row justify-between px-4 py-4">
        <a href="#" class="uppercase text-lg font-semibold tracking-widest">
          TradeTool UI</a
        >
        <button class="rounded-lg md:hidden focus:outline-none">X</button>
      </div>
      <nav class="hidden md:block flex-grow">
        <NuxtLink
          class="block px-4 text-sm py-2 mt-2 hover:bg-gray-700 rounded-lg"
          to="/"
          >Dashboard</NuxtLink
        >
        <NuxtLink
          class="block px-4 text-sm py-2 mt-2 hover:bg-gray-700 rounded-lg"
          to="/trade"
          >Trade</NuxtLink
        >
      </nav>
    </div>
    <div class="flex-grow">
      <Nuxt />
    </div>
  </div>
</template>

<style scoped>
.nuxt-link-exact-active {
  background: #374151;
}
</style>
