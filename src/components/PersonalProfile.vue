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
          <span class="block text-base text-center text-indigo-600 font-semibold tracking-wide uppercase">Personality Test</span>
          <span class="mt-2 block text-3xl text-center leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">Personal Profile</span>
        </h1>
      </div>
      <div class="mt-6 prose prose-indigo prose-lg text-gray-500 mx-auto">
        <figure>
          <img class="w-full rounded-lg" src="@/assets/photo-5.png" alt="" width="1310" height="873">
        </figure>

        <p>
          16 personalities test from <a href="www.16personalities.com" target="_blank">www.16personalities.com</a>.
        </p>

        <figure>
          <img class="w-full rounded-lg" src="@/assets/photo-6.png" alt="" width="1310" height="873">
        </figure>

        <p>
          What's your Learning Style test from <a href="http://www.educationplanner.org/students/self-assessments/learning-styles.shtml" target="_blank">Educationplanner.org</a>.
        </p>

        <figure>
          <img class="w-full rounded-lg" src="@/assets/photo-7.png" alt="" width="1310" height="873">
        </figure>

        <p>
          Big Five Personality Test from <a href="https://openpsychometrics.org/tests/IPIP-BFFM/" target="_blank">Open-Source Psychometrics Project</a>.
        </p>

        <p>
          From the test results, it is clear that I have an interval personality. I don’t like to start conversations and talk to people about their personal lifes. But that doesn’t mean I don’t care about others, I just found it difficult to start chatting about things. However, when someone does tell me about their problems, I am more than happy to help them as best as I can.
        </p>
        <p>
          When working in a team, I won’t be too proactive. I don’t like to take the leading role, and organise everything. However, I will provide my skills and knowledge to others. And I am committed to finish my part of the work.        </p>
        <p>
          When forming a team, it will be better for me and others that I find teammates who like to take the leading role. And also people who are more into communication and have better intel personal skills.
        </p>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: 'PersonalProfile',
}
</script>