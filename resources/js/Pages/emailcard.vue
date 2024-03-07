<script setup>
import { Head, Link } from '@inertiajs/vue3';

</script>

<template>
        <div class="flex items-center justify-center h-screen bg-zinc-700">
                <!-- Card -->
                <div class="bg-zinc-800 p-2 mx-6 rounded-2xl">
                        <!-- Flex container -->
                        <div class="flex flex-col md:flex-row rounded-l-xl">
                          <!-- resim -->
                           <img :src="'/storage/images/image.jpg'" alt="" class="object-fill rounded-xl h-80 md:h-64 md:rounded-l-xl md:rounded-r-none transform hover:scale-105 hover:rounded-xl duration-200">

                                <!-- İçerik -->
                                <div class="p6 md:p-12">
                                    <h2 class="font-serif text-xl font-medium text-center text-white md:text-left">Get diet and fitness in your inbox </h2>
                                    <p class="mx-w-xs my-4 text-xs leading-5 tracking-wide text-center text-white">Eat Better and exercise better.Sign up for the Diet&Firness newsletter</p>

                                        <div class="flex flex-col mt-5 space-y-4 md:space-x-3 md:flex-row md:space-y-0">
                                                <input type="text" placeholder="Enter your email adress" class="p-2 px-4 text-center text-white bg-zinc-800 border border-zinc-600 placeholder:text-xs placeholder:text-center md:text-left placeholder:md:text-left focus:outline-none">

                                                <button class="px-5 py-3 text-xs rounded-md text-zinc-800 bg-lime-500 hover:bg-lime-700 hover:text-white duration-500">
                                                Subscribe
                                                </button>
                                        </div>




                                </div>

                        </div>
                </div>

        </div>



</template>
