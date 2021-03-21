<template>
  <!-- This example requires Tailwind CSS v2.0+ -->
  <nav class="space-y-1 bg-gray-600 bg-opacity-60 rounded-lg p-1" aria-label="Sidebar">
    <!-- Current: "bg-gray-100 text-gray-900", Default: "text-gray-200 hover:bg-gray-50 hover:text-gray-900" -->
    <a href=""
       class="text-gray-200 hover:bg-gray-50 hover:text-gray-900 flex items-center px-3 py-2 text-sm font-medium rounded-md"
       @click.prevent="scroll('top')">
    <span class="truncate">
      <i data-feather="circle"></i>
      Top
    </span>
    </a>

    <a href=""
       class="text-gray-200 hover:bg-gray-50 hover:text-gray-900 flex items-center px-3 py-2 text-sm font-medium rounded-md"
       @click.prevent="scroll('aboutMe')">
    <span class="truncate">
      About Me
    </span>
    </a>

    <a href=""
       class="text-gray-200 hover:bg-gray-50 hover:text-gray-900 flex items-center px-3 py-2 text-sm font-medium rounded-md"
       @click.prevent="scroll('interest')">
    <span class="truncate">
     Interest In IT
    </span>
    </a>

    <a href=""
       class="text-gray-200 hover:bg-gray-50 hover:text-gray-900 flex items-center px-3 py-2 text-sm font-medium rounded-md"
       @click.prevent="scroll('dreamJob')">
    <span class="truncate">
      Dream Job
    </span>
    </a>

    <a href=""
       class="text-gray-200 hover:bg-gray-50 hover:text-gray-900 flex items-center px-3 py-2 text-sm font-medium rounded-md"
       @click.prevent="scroll('profile')">
    <span class="truncate">
      Personal Profile
    </span>
    </a>

    <a href=""
       class="text-gray-200 hover:bg-gray-50 hover:text-gray-900 flex items-center px-3 py-2 text-sm font-medium rounded-md"
       @click.prevent="scroll('project')">
    <span class="truncate">
      Project Idea
    </span>
    </a>
  </nav>

</template>

<script>
export default {
  name: 'SideNav',
  props: {
  },
  data() {
    return {
      currentSection: 'aboutMe',
    }
  },
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