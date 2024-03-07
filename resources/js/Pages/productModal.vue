<script setup>
import { Head, Link } from '@inertiajs/vue3';

</script>

<template>
    <!-- Global Container -->
    <div class="flex items-center justify-center min-h-screen bg-slate-100">
        <!-- Card Container -->
        <div class="flex flex-col p-6 m-3 space-y-10 bg-white rounded-2xl shadow-2xl md:flex-row md:space-y-0 md:space-x-10 md:m-0 md:p-16">
            <!-- resim div -->
            <div>
                <img :src="'/storage/images/headphone.png'" alt="" class="mx-auto duration-200 w-60 hover:scale-105">
            </div>
            <!-- İçerik -->
            <div class="flex flex-col space-y-6">
                <!-- label -->
                <div class="flex flex-col mb-4 space-y-3 text-center md:text-left">
                    <div>
                        <div class="inline-block px-3 py-1 text-sm text-white bg-black rounded-full">
                            Free Shipping
                        </div>
                    </div>

                    <!-- Description  -->
                    <div class="max-w-sm text-2xl font-medium">
                        Razer Kraken Kitty Edit Gaming Headset Quartz
                    </div>

                    <!-- Price -->
                    <div class="flex flex-col mb-4 space-y-3 text-center md:text-left">
                       <p class="line-through">$199</p>
                       <p class="text-5xl font-bold">$99</p>
                       <p class="text-sm font-light text-gray-400">This offer is valid until April 3rd or as long as stock lasts</p>
                    </div>


                    <!-- Button  Group-->
                    <div class="group">
                        <button class="bg-blue-700 w-full transition-all duration-150 text-white border-b-8 border-b-blue-700 rounded-lg group-hover:border-t-8 group-hover:border-b-0 group-hover:bg-blue-700 group-hover:border-t-blue-700 group-hover:shadow-lg">
                            <div class="bg-blue-500 py-4 px-8 duration-150 rounded-lg group-hover:bg-blue-700">
                                Add to card
                            </div>
                        </button>
                    </div>

                    <!-- Stock -->
                    <div class="flex items-center space-x-3 group">
                        <div class="w-3 h-3 bg-green-400 rounded-full group-hover:animate-ping"
                        ></div>
                        <div class="text-sm">50+ pics in stock</div>
                    </div>

                    <!-- Bottom Buttons -->
                    <div class="flex flex-col space-y-4 md:space-y-0 md:space-x-4 md:flex-row">
                        <button class="flex items-center justify-center py-3 px-5 space-x-3 border-2 border-gray-300 rounded-lg shadow-sm hover:bg-opacity-30 hover:shadow-lg hover:-translate-y-0.5 transition-all duration-150">
                            <img :src="'/storage/images/weight.png'" alt="" class="w-8">
                            <span>Add to cart</span>
                        </button>
                        <button class="flex items-center justify-center py-3 px-5 space-x-3 border-2 border-gray-300 rounded-lg shadow-sm hover:bg-opacity-30 hover:shadow-lg hover:-translate-y-0.5 transition-all duration-150">
                            <img :src="'/storage/images/heart.png'" alt="" class="w-8">
                            <span>Add to wishlist</span>
                        </button>
                    </div>

                </div>

            </div>

        </div>


    </div>



</template>
