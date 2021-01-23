<template>
    <div class="main_wrapper">
      <Home></Home>
      <About></About>
      <Skills></Skills>
      <Education></Education>
      <Links></Links>
      <Contact></Contact>
    </div>
</template>
<script>
import Home from './main/Home';
import About from './main/About';
import Skills from './main/Skills';
import Education from './main/Education';
import Links from './main/Links';

export default {
  name: "components",
  components: {
    Home,
    About,
    Skills,
    Links, 
    Education
  }
};
</script>
