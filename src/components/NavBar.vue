<template>
  <nav class="relative max-w-7xl mx-auto flex items-center justify-between px-4 sm:px-6" aria-label="Global">
    <div class="flex items-center flex-1">
      <div class="flex items-center justify-between w-full md:w-auto">
        <a href="#">
          <img class="h-8 w-auto sm:h-10" src="https://tailwindui.com/img/logos/workflow-mark-indigo-500.svg" alt="">
        </a>
      </div>
      <div class="hidden space-x-10 md:flex md:ml-10">
        <a href="#" class="font-medium text-white hover:text-gray-300">About Me</a>

        <a href="#" class="font-medium text-white hover:text-gray-300">Features</a>

        <a href="#" class="font-medium text-white hover:text-gray-300">Marketplace</a>

        <a href="#" class="font-medium text-white hover:text-gray-300">Company</a>
      </div>
    </div>
    <div class="hidden md:flex">
      <a href="#" class="inline-flex items-center px-4 py-2 border border-transparent text-sm font-medium rounded-md text-white bg-gray-600 hover:bg-gray-700">
        Log in
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>