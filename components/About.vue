<template>
  <section id="about" class="bg-[#1A1A29] h-[1000px] w-screen">
    <div class="container mx-auto">
      <div class="text-white flex items-start flex-col">
        <h1 class="text-[50px] text-[#7562E0] font-semibold">About Me:</h1>
        <p class="text-[26px] mt-[10px]">My name is <b class="font-semibold">Abduvosidov Abdulahad</b>.⠀I'm from Tashkent,
          Uzbekistan.⠀I was born in 2007
          in Tashkent.⠀I study at school in the 10th grade.⠀
          I graduated from the center of modern sciences "Najot Ta'lim" in the direction of Full Stack (NodeJS + VueJS).⠀
          I'm a universal programmer who
          can develop a functional product from scratch.⠀I'm a specialist who understands both the
          Back-end component
          and the Front-end.
        </p>
      </div>
      <div class="flex gap-10 items-center">
        <h1 class="text-[50px] text-[#7562E0] font-semibold mt-[50px]">What I'm capable of:</h1>
      </div>
      <div class="flex gap-[200px] justify-center mt-[40px]">
        <div v-for="el in  icando"
          class="w-[400px] h-[400px] flex flex-col bg-[#7562E0] justify-center pt-[17px] text-white">
          <img :src="`/icons/${el.img}`" alt="" class="w-[100px] h-[px] ml-[40px]" />
          <span class="mt-[10px] text-[40px] font-semibold mb-[-50px] ml-[40px]">{{ el.title }}</span>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const icando = [
  {
    id: 1,
    title: "UI & UX DESIGNING",
    img: "rulerpen.svg",
  },
  {
    id: 2,
    title: "WEB DEVELOPMENT",
    img: "code.svg",
  }
];
</script>

<style lang="css" src="../public/css/animation.css" scoped></style>