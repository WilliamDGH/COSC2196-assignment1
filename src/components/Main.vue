<template>
  <main class="mt-16 sm:mt-24">
    <div class="mx-auto max-w-7xl">
      <div class="lg:grid lg:grid-cols-12 lg:gap-8">
        <div class="px-4 sm:px-6 sm:text-center md:max-w-2xl md:mx-auto lg:col-span-6 lg:text-left lg:flex lg:items-center">
          <div>
            <h1 class="mt-4 text-4xl tracking-tight font-extrabold text-white sm:mt-5 sm:leading-none lg:mt-6 lg:text-5xl xl:text-6xl">
              <span class="md:block">Guanhua Ding</span>
              <span class="text-indigo-400 md:block">Software Developer</span>
            </h1>
            <p class="mt-3 text-base text-gray-300 sm:mt-5 sm:text-xl lg:text-lg xl:text-xl">
              I am a junior software developer who is passionate about the ever changing nature of the tech industry.
            </p>
            <div class="mt-5 pt-5 w-full sm:mx-auto sm:max-w-lg lg:ml-0">
              <div class="">
                <div class="flex justify-start px-1 text-xl text-gray-400">
                  <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-book"><path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"></path><path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"></path></svg>
                  <span class="ml-4">Guanhua Ding</span>
                </div>
                <div class="flex justify-start px-1 text-xl text-gray-400 mt-2">
                  <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-user"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                  <span class="ml-4">s3644556</span>
                </div>
                <div class="flex justify-start px-1 text-xl text-gray-400 mt-2">
                  <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-mail"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
                  <span class="ml-4">S3644556@student.rmit.edu.au</span>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="sm:mt-24 lg:mt-0 lg:col-span-6">
          <img src="@/assets/main.jpeg" alt="coding" class="rounded-lg opacity-80">
        </div>
      </div>
    </div>
  </main>
</template>

<script>

export default {
  name: 'Main',
}
</script>