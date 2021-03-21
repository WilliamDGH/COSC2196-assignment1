<template>
  <div class="relative bg-gray-800 overflow-hidden">
    <div class="relative pt-6 pb-16 sm:pb-24">
      <NavBar ref="top"/>
      <Main />
    </div>
  </div>
  <div class="fixed bottom-10 right-10 z-50">
    <SideNav />
  </div>
  <AboutMe class="pb-4" ref="aboutMe" />

  <Interest class="pb-4" ref="interest" />

  <DreamJob class="pb-4" ref="dreamJob" />

  <PersonalProfile class="pb-4" ref="profile"/>

  <ProjectIdea class="pb-4" ref="project" />

  <Footer />

</template>

<script>

import NavBar from "./components/NavBar";
import AboutMe from "./components/AboutMe";
import DreamJob from "./components/DreamJob";
import Interest from "./components/Interest";
import SideNav from "./components/SideNav";
import Footer from "./components/Footer";
import Main from "./components/Main";
import PersonalProfile from "./components/PersonalProfile";
import ProjectIdea from "./components/ProjectIdea";
export default {
  name: 'App',
  components: {
    ProjectIdea,
    PersonalProfile,
    Main,
    Footer,
    SideNav,
    Interest,
    DreamJob,
    AboutMe,
    NavBar
  },
  data: function () {
    return {
      darkMode: 'media',
    }
  },
}
</script>
