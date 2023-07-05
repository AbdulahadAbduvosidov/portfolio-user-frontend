<template>
    <section  class="bg-[#1A1A29] h-[1000px] w-screen">
        <div class="container mx-auto">
            <div>
                <h1 class="text-[#7562E0] text-[60px] text-start font-semibold">Projects:</h1>
                <div class="grid grid-cols-3 gap-[60px] text-white mt-[30px]">
                    <div class="flex flex-col rounded-[16px] duration-700 mx-auto p-[20px] shadow-lg shadow-[#7562E0]">
                        <div class="flex justify-center">
                            <img src="../public/img/alibaba.png" class="w-[400px] h-[220px] border-[2px] border-[#7562E0] rounded-[8px]" alt="">
                        </div>
                        <h1 class="text-[28px] mt-[30px] text-[#7562E0]">Alibaba</h1>
                        <p class="text-[20px] mt-[10px]">This is clon site of Alibaba. In this site you can order anything.</p>
                        <p class="text-[18px] flex flex-cols mt-[20px] items-center justify-end gap-1"><i class='bx bx-code-alt text-[34px] text-[#7562E0]'></i>Frontend</p>
                        <div class="flex justify-center mt-[40px]">
                            <NuxtLink to="https://alibaba-6q3s.vercel.app">
                                <button class="live_btn bg-[#7562E0] w-[200px] h-[50px] rounded-[8px] text-[20px]">View Live</button>
                            </NuxtLink>
                        </div>
                    </div>
                    <div class="flex flex-col rounded-[16px] duration-700 mx-auto p-[20px] shadow-lg shadow-[#7562E0]">
                        <div class="flex justify-center">
                            <img src="../public/img/academy.png" class="w-[400px] h-[220px] border-[2px] border-[#7562E0] rounded-[8px]" alt="">
                        </div>
                        <h1 class="text-[28px] mt-[30px] text-[#7562E0]">Academy</h1>
                        <p class="text-[20px] mt-[10px]">in this site you can get detailed information about students and teachers.</p>
                        <p class="text-[18px] flex flex-cols mt-[20px] items-center justify-end gap-1"><i class='bx bx-code-alt text-[34px] text-[#7562E0]'></i>Frontend</p>
                        <div class="flex justify-center mt-[40px]">
                            <NuxtLink to="https://exam-sigma.vercel.app/">
                                <button class="live_btn bg-[#7562E0] w-[200px] h-[50px] rounded-[8px] text-[20px]">View Live</button>
                            </NuxtLink>
                        </div>
                    </div>
                    <div class="flex flex-col rounded-[16px] duration-700 mx-auto p-[20px] shadow-lg shadow-[#7562E0]">
                        <div class="flex justify-center">
                            <img src="../public/img/edu_test.png" class="w-[400px] h-[220px] border-[2px] border-[#7562E0] rounded-[8px]" alt="">
                        </div>
                        <h1 class="text-[28px] mt-[30px] text-[#7562E0]">Test system</h1>
                        <p class="text-[20px] mt-[10px]">in this site you can get detailed information about testing students.</p>
                        <p class="text-[18px] flex flex-cols mt-[20px] items-center justify-end gap-1"><i class='bx bx-code-alt text-[34px] text-[#7562E0]'></i>Frontend</p>
                        <div class="flex justify-center mt-[40px]">
                            <NuxtLink to="https://github.com/Test-system-edu/frontend">
                                <button class="live_btn bg-[#7562E0] w-[200px] h-[50px] rounded-[8px] text-[20px]">View Live</button>
                            </NuxtLink>
                        </div>
                    </div>
                </div>
                <div class="swiper">
                    <!-- Additional required wrapper -->
                    <div class="swiper-wrapper">
                    <!-- Slide 1 -->
                    <div class="swiper-slide">  
                        <div class="swiper-image">
                            <div class="image"></div>
                        </div>
                    </div>
                    <!-- Slide 2 -->
                    <div class="swiper-slide">
                        <div class="swiper-image">
                            <div class="image"></div>
                        </div>
                    </div>
                    <!-- Slide 3 -->
                    <div class="swiper-slide">
                        <div class="swiper-image">
                            <div class="image"></div>
                        </div>
                    </div>
                    </div>
                    
                    <!-- If we need navigation buttons -->
                    <div class="swiper-button-prev"></div>
                    <div class="swiper-button-next"></div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
</script>

<style lang="css" scoped>

.live_btn:hover{
    background-color: #181824;
    border: 2px solid #7562E0;
    transition-duration: 300ms;
}

</style>