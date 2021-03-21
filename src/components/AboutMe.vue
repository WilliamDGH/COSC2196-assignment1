<template>
  <div class="relative py-16 bg-white overflow-hidden" id="about">
    <div class="hidden lg:block lg:absolute lg:inset-y-0 lg:h-full lg:w-full">
      <div class="relative h-full text-lg max-w-prose mx-auto" aria-hidden="true">
        <svg class="absolute top-12 left-full transform translate-x-32" width="404" height="384" fill="none" viewBox="0 0 404 384">
          <defs>
            <pattern id="74b3fd99-0a6f-4271-bef2-e80eeafdf357" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
              <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
            </pattern>
          </defs>
          <rect width="404" height="384" fill="url(#74b3fd99-0a6f-4271-bef2-e80eeafdf357)" />
        </svg>
        <svg class="absolute top-1/2 right-full transform -translate-y-1/2 -translate-x-32" width="404" height="384" fill="none" viewBox="0 0 404 384">
          <defs>
            <pattern id="f210dbf6-a58d-4871-961e-36d5016a0f49" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
              <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
            </pattern>
          </defs>
          <rect width="404" height="384" fill="url(#f210dbf6-a58d-4871-961e-36d5016a0f49)" />
        </svg>
        <svg class="absolute bottom-12 left-full transform translate-x-32" width="404" height="384" fill="none" viewBox="0 0 404 384">
          <defs>
            <pattern id="d3eb07ae-5182-43e6-857d-35c643af9034" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
              <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
            </pattern>
          </defs>
          <rect width="404" height="384" fill="url(#d3eb07ae-5182-43e6-857d-35c643af9034)" />
        </svg>
      </div>
    </div>
    <div class="relative px-4 sm:px-6 lg:px-8">
      <div class="text-lg max-w-prose mx-auto">
        <h1>
          <span class="block text-base text-center text-indigo-600 font-semibold tracking-wide uppercase">GUANHUA DING</span>
          <span class="mt-2 block text-3xl text-center leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">Software Developer</span>
        </h1>
      </div>
      <div class="mt-6 prose prose-indigo prose-lg text-gray-500 mx-auto">
        <p>
          I am a junior software developer who is passionate about the ever changing nature of the tech industry. After trying to teach myself how to code for over a year or so via online courses such as Udemy I decided to quit retail to make a full time commitment to becoming a Web Developer.
        </p>
        <p>
          I Grew up in China, and have spent the last 8 years in Australia. This experience gives me a more broad view of different cultures and lifestyles. I speak Chinese and English, and follow the trend in the tech industry in both China and the west.
        </p>
        <figure>
          <img class="w-full rounded-lg" src="@/assets/photo-1.jpeg" alt="" width="1310" height="873">
          <figcaption class="mt-3 flex text-sm text-gray-500">
            <!-- Heroicon name: solid/camera -->
            <svg class="flex-none w-5 h-5 text-gray-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
              <path fill-rule="evenodd" d="M4 5a2 2 0 00-2 2v8a2 2 0 002 2h12a2 2 0 002-2V7a2 2 0 00-2-2h-1.586a1 1 0 01-.707-.293l-1.121-1.121A2 2 0 0011.172 3H8.828a2 2 0 00-1.414.586L6.293 4.707A1 1 0 015.586 5H4zm6 9a3 3 0 100-6 3 3 0 000 6z" clip-rule="evenodd" />
            </svg>
            <span class="ml-2"> Me and my son Lucas in Santorini, Greece</span>
          </figcaption>
        </figure>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: 'AboutMe',
}
</script>