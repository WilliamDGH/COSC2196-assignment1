<template>
  <nav class="relative max-w-7xl mx-auto flex items-center justify-between px-4 sm:px-6" aria-label="Global">
    <div class="flex items-center flex-1">
      <div class="flex items-center justify-between w-full md:w-auto">
        <a href="#">
          <img class="h-8 w-auto sm:h-10" src="https://tailwindui.com/img/logos/workflow-mark-indigo-500.svg" alt="">
        </a>
      </div>
      <div class="hidden space-x-10 md:flex md:ml-10">
        <a href="" class="font-medium text-white hover:text-gray-300" @click.prevent="scroll('aboutMe')">About Me</a>

        <a href="" class="font-medium text-white hover:text-gray-300" @click.prevent="scroll('interest')">Interest In IT</a>

        <a href="" class="font-medium text-white hover:text-gray-300" @click.prevent="scroll('dreamJob')">Dream Job</a>


        <a href="" class="font-medium text-white hover:text-gray-300">Company</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
  methods: {
    scroll(sectionRef) {
      const sectionElement = this.$parent.$refs[sectionRef].$el

      if (sectionElement) {
        // Use el.scrollIntoView() to instantly scroll to the element
        this.$nextTick(() => {
          sectionElement.scrollIntoView({
            behavior: 'smooth',
          })
        })
      }
    }
  },
}
</script>