<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <!-- <HelloWorld msg="Hello Vue 3 + Vite" /> -->
  <div class="flex items-center justify-center mt-5">

  <div class="bg-blue-900 w-1/8 p-10 h-auto">
    <div class="flex items-center justify-center mb-10">
      <img src="./assets/studphoto.jpg" alt="" class="w-20 border-2 border-gray-700">
    </div>
    <h1 class="text-gray-400 uppercase tracking-widest text-lg font-bold">INFORMATION</h1>
    <hr class="w-1/6 mb-5">
    <h1 class="text-gray-400 text-sm">Name: Mohammad Farhan Haq'em bin Mohammad Edy Sumardi</h1>
    <h1 class="text-gray-400 text-sm">Gender: Male</h1>
    <h1 class="text-gray-400 text-sm">Age: 21</h1>
    <h1 class="text-gray-400 text-sm">D.O.B: 15/02/2001</h1>
    <hr class="my-5">
        <h1 class="text-gray-400 uppercase tracking-widest text-lg font-bold">Contact</h1>
    <hr class="w-1/6 mb-5">
    <h1 class="text-gray-400 text-sm">20FTT1451@student.pb.edu.bn</h1>
    <h1 class="text-gray-400 text-sm">Bahit was here</h1>
    <h1 class="text-gray-400 text-sm">Negara Brunei Darussalam</h1>
    <h1 class="text-gray-400 text-sm">github.com/frhaqem</h1>
    <hr class="my-5">
    <h1 class="text-gray-400 mt-2 uppercase tracking-widest text-lg font-bold">EDUCATION</h1>
    <hr class="w-1/6 mb-5">
    <h1 class="text-gray-400 text-sm uppercase font-semibold tracking-wider">O' Level</h1>
    <h1 class="text-gray-500 text-sm"><span class="italic">Seri Mulia Sarjana School</span>, <span class="text-gray-400 font-semibold italic">Brunei</span> / 2013 - 2017</h1>
    <br>
    <h1 class="text-gray-400 text-sm uppercase font-semibold tracking-wider">A' Level</h1>
    <h1 class="text-gray-500 text-sm"><span class="italic">Maktab Duli PMAMB</span>, <span class="text-gray-400 font-semibold italic">Brunei</span> / 2018 - 2019</h1>
    <br>
       <h1 class="text-gray-400 text-sm uppercase font-semibold tracking-wider">Diploma Level 5 in Web Development</h1>
    <h1 class="text-gray-500 text-sm"><span class="italic">Politeknik Brunei</span>, <span class="text-gray-400 font-semibold italic">Brunei</span> / 2020 - current</h1>
    <hr class="my-5">
    <!-- <h1 class="text-gray-400 mt-2 uppercase tracking-widest text-lg font-bold">SKILLS</h1>
    <hr class="w-1/6 mb-5"> -->
    <!-- <ul>
      <li class="text-gray-500 text-sm list-disc ml-4">Adobe Photoshop</li>
      <li class="text-gray-500 text-sm list-disc ml-4">Adobe Illustrator</li>
      <li class="text-gray-500 text-sm list-disc ml-4">Adobe After Effects</li>
      <li class="text-gray-500 text-sm list-disc ml-4">Microsoft Power Point</li>
      <li class="text-gray-500 text-sm list-disc ml-4">Microsoft Word</li>
      <li class="text-gray-500 text-sm list-disc ml-4 mb-1">Adobe InDesign</li>
    </ul> -->
  </div>

  <div class="bg-white w-7/12 p-10 h-auto">
    <h1 class="text-gray-500">
      
      <!-- A resourceful individual with a proven track record in implementing successful
      marketing strategies, boosting organic traffic, and improving search rankings seeks a position of Marketing
      Associate at ABC company to maximize brand awareness and revenue through integrated marketing
      communications. -->

      Hello! This page is currently used for WADT Assignment 3.
      
      </h1>
    <h1 class="font-semibold uppercase tracking-wider my-6 text-gray-500">Hobbies:</h1>
    <h1 class="text-gray-600 font-semibold">Playing PC Games</h1>
    <ul class="list-disc ml-5 text-gray-500">
      <li>CSGO</li>
      <li>Valorant</li>
      <li>Apex Legends</li>
    </ul>
    <h1 class="text-gray-600 font-semibold mt-3">Working Out</h1>
    <!-- <ul class="list-disc ml-5 text-gray-500">
      <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
      <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
      <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
    </ul> -->
    <h1 class="text-gray-600 font-semibold mt-3">Playing Sports</h1>
    <ul class="list-disc ml-5 text-gray-500">
      <li>Football/Futsal</li>
      <li>Frisbee</li>
      <li>Touch Rugby</li>
    </ul>
    <br>
     <h1 class="font-semibold uppercase tracking-wider my-6 text-gray-500">SKILLS:</h1>
        <h1 class="text-gray-600 font-semibold mt-3">Adobe</h1>
    <ul class="list-disc ml-5 text-gray-500">
      <li>Photoshop</li>
      <li>After Effects</li>
      <li>Illustrator</li>
    </ul>
    <h1 class="text-gray-600 font-semibold mt-3">Microsoft</h1>
    <ul class="list-disc ml-5 text-gray-500">
      <li>Powerpoint</li>
      <li>Excel</li>
      <li>Word</li>
      <li>Visio</li>
      <li>Project</li>
    </ul>
     <h1 class="text-gray-600 font-semibold mt-3">Text Editors</h1>
    <ul class="list-disc ml-5 text-gray-500">
      <li>Sublime</li>
      <li>Visual Studio Code</li>
    </ul>
  </div>
</div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
body {
  background-color: #e2e8f0
}
</style>
