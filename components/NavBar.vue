<template>
  <nav
    class="relative flex items-center justify-between sm:h-10 lg:justify-start"
    aria-label="Global"
  >
    <div class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-0">
      <div class="flex items-center justify-between w-full md:w-auto">
        <a href="/" class="logo text-2xl">Malcolm X</a>
      </div>
    </div>
    <div class="md:ml-10 md:pr-4 md:space-x-8">
      <nuxt-link to="/events" class="text-gray-700 hover:text-gray-900"
        >Events & Videos</nuxt-link
      >

      <nuxt-link to="/quotes" class="text-gray-700 hover:text-gray-900 ml-4"
        >Quotes</nuxt-link
      >
    </div>
  </nav>
</template>

<script>
export default {}
</script>

<style>
.logo {
  font-family: 'Merriweather', sans-serif;
}
</style>
