<template>
    <div>
      <Home></Home>
      <About></About>
      <Skills></Skills>
      <Education></Education>
      <Links></Links>
        <!-- <hero></hero> -->
        <!-- <basic-elements></basic-elements> -->
        <!-- <inputs></inputs> -->
        <!-- <custom-controls></custom-controls> -->
        <!-- <navigation></navigation> -->
        <!-- <javascript-components></javascript-components> -->
        <!-- <icons></icons> -->
        <!-- <examples></examples> -->
        <!-- <download-section></download-section> -->
        <!-- <carousel></carousel> -->
    </div>
</template>
<script>
import Home from './main/Home';
import About from './main/About';
import Skills from './main/Skills';
import Education from './main/Education';
import Links from './main/Links';



import Hero from "./components/Hero";
import BasicElements from "./components/BasicElements";
import Inputs from "./components/Inputs";
import CustomControls from "./components/CustomControls";
import Navigation from "./components/Navigation";
import JavascriptComponents from "./components/JavascriptComponents";
import Carousel from "./components/Carousel";
import Icons from "./components/Icons";
import Examples from "./components/Examples";
import DownloadSection from "./components/DownloadSection";


export default {
  name: "components",
  components: {
    Home,
    About,
    Skills,
    Links,
    Hero,
    BasicElements,
    Inputs,
    CustomControls,
    Navigation,
    JavascriptComponents,
    Carousel,
    Icons,
    Examples,
    DownloadSection,
    Education
  }
};
</script>
