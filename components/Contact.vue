<template>
  <section class="bg-[#1A1A29] h-[770px] w-screen">
    <div class="container mx-auto">
      <div class="flex">
        <div class="text-white flex items-start flex-col w-1/2">
          <h1 class="text-[50px] text-[#7562E0] font-semibold">Connect with me:</h1>
          <p class="text-[26px] mt-[10px]">Satisfied with me? Please connect
          </p>
          <div class="mt-[30px] flex gap-10">
            <NuxtLink to="https://t.me/Abdulahad_1">
              <img class="h-[50px]" src="../public/icons/tg.svg" alt="">
            </NuxtLink>
            <NuxtLink to="https://www.instagram.com/a_abdulahad1">
              <img class="h-[50px]" src="../public/icons/ins.svg" alt="">
            </NuxtLink>
            <NuxtLink to="https://mail.google.com/mail/u/0/#search/abduaxadabduvosidov%40gmail.com">
              <img class="h-[50px]" src="../public/icons/gmail.svg" alt="">
            </NuxtLink>
          </div>
        </div>
        <div class="text-white flex items-start flex-col w-1/2">
          <h1 class=" mt-[10px] text-[38px] text-white">Contact me, lets create magic togetger</h1>
          <input class="p-5 text-[22px] w-full h-[100px] mt-10 rounded-xl bg-gray-700 focus:outline-none" type="text" placeholder="Name:">
          <input class="p-5 text-[22px] w-full h-[100px] mt-7 rounded-xl bg-gray-700 focus:outline-none" type="text" placeholder="Email:">
          <textarea class="p-5 text-[22px] w-full h-[150px] mt-7 rounded-xl bg-gray-700 focus:outline-none" name="" id="" cols="30" rows="10" placeholder="Message:"></textarea>
          <button class="w-2/5 mt-7 rounded-xl h-[80px] text-[22px] bg-[#7562E0]">Send</button>
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