<script setup>
import { Head, Link } from '@inertiajs/vue3';

</script>

<template>
    <!-- Hero Section -->
    <section id="hero">
        <!-- Heronun Containeri  -->
        <div class="container max-w-6xl mx-auto px-6 py-12">

            <!-- Menü ve Logo Container -->
            <nav class="flex items-center justify-between font-bold text-white">
                <!-- Logo -->
                <img :src="'/storage/images/loopstudios/images/logo.svg'" alt="">
                <!-- Menü -->
                <div class="hidden h-10 font-serif md:flex md:space-x-8">
                    <div class="group">
                        <a href="#">About</a>
                        <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
                    </div>
                    <div class="group">
                        <a href="#">Careear</a>
                        <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
                    </div>
                    <div class="group">
                        <a href="#">Events</a>
                        <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
                    </div>
                    <div class="group">
                        <a href="#">Products</a>
                        <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
                    </div>
                    <div class="group">
                        <a href="#">Support</a>
                        <div class="mx-2 group-hover:border-b group-hover:border-blue-50"></div>
                    </div>
                </div>

                <!-- Hamburger menu -->
            </nav>
            <!-- Mobile menü -->

            <div class="max-w-lg mt-32 mb-32 p-4 font-sans text-4xl text-white uppercase border-2 md:p-10 md:m-32 md:mx-0 md:text-6xl">
                Impressive Experiences That Deliver
            </div>

        </div>


    </section>

    <!-- Feature Section -->
    <section id="feature">
        <!-- fature container -->
        <div class="relative container flex flex-col max-w-6xl mx-auto my-32 px-6 text-gray-900 md:flex-row md:px-0">
            <!-- Image -->
            <img :src="'/storage/images/loopstudios/images/desktop/image-interactive.jpg'" alt="">
            <!-- Text Container -->
            <div class="top-48 pr-0 bg-white md:absolute md:right-0 md:py-20 md:pl-20">
                <h2 class="max-w-lg mt-10 mb-6 font-sans text-4xl text-center text-gray-900 uppercase md:text-5xl md:mt-0 md:text-left">
                    The Leader in interactive VR
                </h2>
                <p class="max-w-md text-center md:text-left">
                    Founded in 2011, Loopstudios has been producing world-class virtual reality projects for some of the best companies around the globe. Our award-winning creations have transformed businesses through digital experiences that bind to their brand.
                </p>
            </div>

        </div>
    </section>

    <!-- Creations Section -->
    <section id="creations">
        <!-- Creations Container -->
        <div class="container max-w-6xl mx-auto my-32 px-6 text-gray-900 md:px-0">
            <!-- Creations Header -->
            <div class="flex justify-center mb-20 md:justify-between">
                <h2 class="text-4xl text-center uppercase md:text-left md:text-5xl">
                    Our Creations
                </h2>
                <button class="hidden px-10 py-2 my-0 font-bold tracking-widest uppercase border-2 border-black font-serif hover:bg-black hover:text-white md:block">
                    See All
                </button>
            </div>

            <!-- Items Container -->
        </div>
    </section>

</template>
