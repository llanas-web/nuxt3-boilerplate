<template>
  <div class="flex flex-col w-full h-screen overflow-hidden bg-green-50">
    <header class="w-full h-16 bg-green-500">
      <nav
        class="flex items-center justify-center w-full h-full text-center text-black"
      >
        <h2 class="text-2xl font-bold text-white">Nuxt 3</h2>
      </nav>
    </header>
    <main class="flex-grow w-full h-full p-4 mx-auto max-w-7xl">
      <NuxtPage />
    </main>
    <footer class="flex items-center justify-center w-full h-16 text-black">
      <p class="text-gray-700">
        My Nuxt App &copy; {{ new Date().getFullYear() }}
      </p>
    </footer>
  </div>
</template>
