<template>
    <section id="about" class="bg-[#1A1A29] h-[1000px] w-screen">
        <div class="container mx-auto">
            <div class="text-white flex items-start flex-col">
                <h1 class="text-[50px] text-[#7562E0] font-semibold">About Me:</h1>
                <p class="text-[26px] mt-[10px]">My name's <b class="font-semibold">Abdulahad</b>, I'm 15 years old and I'm
                    from Tashkent, Uzbekistan. I am a frontend developer. Full Stack Developer is a universal programmer who
                    can develop a functional product from scratch. Fullstack developer is a specialist who understands both the Back-end component
                    and the Front-end.
                </p>
            </div>
            <div class="text-[#7562E0] flex gap-10 items-center">
                <h1 class="font-semibold text-[160px]">5+</h1>
                <h1 class="text-[33px] text-white">Years of experience. Specialised in building apps, while
                    ensuring a seamless
                    web experience for end users.</h1>
            </div>
            <div class="flex gap-[200px] justify-center">
                <div v-for="el in  icando" class="w-[400px] h-[400px] flex flex-col bg-[#7562E0] justify-center pt-[17px] text-white">
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