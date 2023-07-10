<template>
  <section id="contact" class="bg-[#1A1A29] h-[350px] w-screen">
    <div class="container mx-auto">
      <div class="flex">
        <div class="text-white flex items-start flex-col">
          <p class="text-[38px] font-semibold text-[#7562E0]">Satisfied with me?
          </p>
          <p class="text-[23px] py-1 mt-[5px] flex"><b>Email:</b>⠀abduaxadabduvosidov@gmail.com</p>
          <p class="text-[23px] flex"><b>Phone number:</b>⠀+998 99 000 55 87</p>
          <div class="mt-[20px] flex gap-10">
            <NuxtLink to="https://t.me/Abdulahad_1">
              <img class="h-[50px]" src="../public/icons/tg.svg" alt="">
            </NuxtLink>
            <NuxtLink to="https://www.instagram.com/a_abdulahad1">
              <img class="h-[50px]" src="../public/icons/ins.svg" alt="">
            </NuxtLink>
            <NuxtLink to="https://github.com/AbdulahadAbduvosidov">
              <img class="h-[50px]" src="../public/icons/github.svg" alt="">
            </NuxtLink>
          </div>
        </div>
        <!-- <div class="text-white flex items-start flex-col w-1/2">
          <h1 class=" mt-[10px] text-[38px] text-white">Contact me, lets create magic togetger</h1>
          <input class="p-5 text-[22px] w-full h-[100px] mt-10 rounded-xl bg-gray-700 focus:outline-none" type="text" placeholder="Name:">
          <input class="p-5 text-[22px] w-full h-[100px] mt-7 rounded-xl bg-gray-700 focus:outline-none" type="text" placeholder="Email:">
          <textarea class="p-5 text-[22px] w-full h-[150px] mt-7 rounded-xl bg-gray-700 focus:outline-none" name="" id="" cols="30" rows="10" placeholder="Message:"></textarea>
          <button class="w-2/5 mt-7 rounded-xl h-[80px] text-[22px] bg-[#7562E0]">Send</button>
        </div> -->
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
