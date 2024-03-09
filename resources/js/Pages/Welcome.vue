<script setup>
import { Head, Link } from '@inertiajs/vue3';

</script>

<template>
    <!-- Hero Section -->
    <section id="hero">
        <div class="max-w-6xl mx-auto text-center mb-40 px-10 pt-16">
            <img :src="'/storage/images/clipboard/logo.svg'" alt="" class="mx-auto my-16">

            <h3 class="mb-8 text-2xl font-bold text-gray-500 md:text-5xl">
                "Çiftçiler ve Firmalar Arasındaki Köprü:
            </h3>
            <p class="max-w-3xl mx-auto mb-10 text-2zl text-gray-400">
                Bildirimlerinizin kontrolü artık elinizde, sizden izinsiz adınıza bildirim yapılmasına  müsade etmeyin
            </p>

              <!-- Button Container -->
              <div class="flex flex-col justify-center w-full space-y-6 text.xl text-white md:flex-row md:space-y-0 md:space-x-4">
                <a href="#" class="p-4 px-8 rounded-full shadow-lg bg-green-500 duration-200 hover:opacity-80">Download for İOS</a>
                <a href="#" class="p-4 px-8 rounded-full shadow-lg bg-blue-500 duration-200 hover:opacity-80">Download for Mac</a>

              </div>
        </div>


    </section>
</template>
