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

     <!-- Snippets sections -->
    <section id="snippets">
        <div class="max-x-6xl mx-auto text-center my-20 px-10">
            <h3 class="mb-8 text-4xl font-bold text-gray-500 md:text-5xl">
                Keep track of your snippets
            </h3>
            <p class="max-w-3xl mx-auto mb-24 text-xl leading-9 text-center text-gray-400">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium, repellendus dicta! Error quas eveniet accusantium sed odit debitis quasi, deserunt perspiciatis maxime sapiente, voluptates quis repudiandae dolorum aut fuga impedit.
            </p>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features">
        <div class="max-w-6xl mx-auto text-center my-20 px-10">
            <div class="relative flex flex-col md:flex-row md:space-x-32">
                <!-- image -->
                    <div class="md:w-1/2">
                        <img :src="'/storage/images/clipboard/image-computer.png'" alt="" class="md:absolute top-0 right-[50%]">
                    </div>
                <!-- Items Container -->
                <div class="flex flex-col mt-16 mb-24 space-y-12 text-xl md:w-1/2 md:mb-60 md:text-left md:pl-16">
                        <!-- Item 1 -->
                        <div>
                            <h5 class="mb-2 text-2xl font-bold text-gray-600">Quick Search</h5>
                            <p class="max-w-md text-gray-400">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sint accusantium nemo nostrum fuga rem dolores officia quo cumque! Beatae, eveniet.</p>
                        </div>
                         <!-- Item 2 -->
                         <div>
                            <h5 class="mb-2 text-2xl font-bold text-gray-600">iCloud Sync</h5>
                            <p class="max-w-md text-gray-400">Voluptatem ab assumenda est facere quia voluptas laborum, sunt molestiae quae consequatur esse dignissimos, suscipit laboriosam et sint?</p>
                        </div>
                         <!-- Item 3 -->
                         <div>
                            <h5 class="mb-2 text-2xl font-bold text-gray-600">Completely History</h5>
                            <p class="max-w-md text-gray-400">Veniam deserunt fugit repudiandae asperiores porro, laudantium similique itaque modi ullam. Delectus ipsam consequatur voluptatem aspernatur laboriosam libero.</p>
                        </div>
                </div>
            </div>

        </div>

    </section>

    <!-- Access Anywhere Section -->
    <section id="access">
        <div class="max-w-6xl mx-auto text-center my-20 px-10">
            <h5 class="text-2xl font-bold text-gray-600">Access Clipboard Anywhere</h5>
            <p class="max-w-3xl mx-auto mb-24 text-xl leading-9 text-center text-gray-400">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium, repellendus dicta! Error quas eveniet accusantium sed odit debitis quasi, deserunt perspiciatis maxime sapiente, voluptates quis repudiandae dolorum aut fuga impedit.
            </p>

            <img :src="'/storage/images/clipboard/image-devices.png'" alt="" class="mx-auto">
        </div>
    </section>

     <!-- Supercharge Section -->
     <section id="supercharge">
      <div class="max-w-6xl mx-auto text-center my-20 px-10">
        <h3 class="mb-8 text-4xl font-bold text-gray-500 md:text-5xl">Supercharge your workflow</h3>
        <p class="max-w-3xl mx-auto mb-16 text-xl leading-9 text-center text-gray-400">
          We've got the tools to boost your productivity.
        </p>
        <!-- Items Container -->
        <div class="flex flex-col items-center justify-between space-y-16 md:flex-row md:space-y-0 md:space-x-12">
          <!-- Item 1 -->
          <div class="flex flex-col items-center space-y-5">
            <img :src="'/storage/images/clipboard/icon-blacklist.svg'" alt="" class="mb-6" />
            <h5>Create Blacklists</h5>
            <p class="max-w-md text-grayishBlue">
              Easily search your snippets by content, category, web address,
              application, and more.
            </p>
          </div>

          <!-- Item 2 -->
          <div class="flex flex-col items-center space-y-5">
            <img :src="'/storage/images/clipboard/icon-text.svg'" alt="" class="mb-6" />
            <h5>Plain Text Snippets</h5>
            <p class="max-w-md text-grayishBlue">
              Remove unwanted formatting from copied text for a consistent look.
            </p>
          </div>

          <!-- Item 3 -->
          <div class="flex flex-col items-center space-y-5">
            <img :src="'/storage/images/clipboard/icon-preview.svg'" alt="" class="mb-6" />
            <h5>Sneak Preview</h5>
            <p class="max-w-md text-grayishBlue">
              Quick preview of all snippets on your Clipboard for easy access.
            </p>
          </div>
        </div>
      </div>
    </section>

     <!-- References Section -->
     <section id="references">
      <div class="flex flex-col items-center justify-between max-w-6xl px-10 mx-auto space-y-16 my-44 md:flex-row md:space-y-0">
        <img :src="'/storage/images/clipboard/logo-google.png'" alt="" />
        <img :src="'/storage/images/clipboard/logo-ibm.png'" alt="" />
        <img :src="'/storage/images/clipboard/logo-microsoft.png'" alt="" />
        <img :src="'/storage/images/clipboard/logo-hp.png'" alt="" />
        <img :src="'/storage/images/clipboard/logo-vector-graphics.png'" alt="" />
      </div>
    </section>

     <!-- Bottom CTA Section -->
     <section id="bottom">
        <div class="max-w-6xl mx-auto text-center my-20 px-10">
        <h3>Clipboard for iOS and MacOS</h3>
        <p class="max-w-3xl mx-auto leading-9 text-center text-xl text-gray-300 mb-10">
          Available for free on the App Store. Download for Mac or iOS, sync
          with iCloud and you're ready to start adding to your clipboard.
        </p>

        <!-- Button Container -->
        <div class="flex flex-col justify-center w-full space-y-6 text-xl text-white md:flex-row md:space-y-0 md:space-x-4">
          <a href="#" class="p-4 px-8 rounded-full shadow-lg bg-cyan-500 duration-200 hover:opacity-80">Download for iOS</a>
          <a href="#" class="p-4 px-8 rounded-full shadow-lg bg-blue-400 duration-200 hover:opacity-80">Download for Mac</a>
        </div>
      </div>
    </section>

    <footer class="bg-gray-50">
        <div class="max-w-6xl mx-auto text-center my-20 px-10">
        <div class="flex flex-col items-center justify-between md:flex-row">
          <!-- Image -->
          <img :src="'/storage/images/clipboard/logo.svg'" alt="" class="scale-50" />
          <!-- Container for Menus & Social -->
          <div class="flex flex-col items-center justify-between flex-1 mb-10 space-y-6 md:flex-row md:mb-0 md:space-y-0 text-gray-700">
            <!-- Menus -->
            <div class="flex flex-col space-y-4 md:flex-row md:ml-24 md:space-x-24 md:space-y-0">
              <!-- Menu 1 -->
              <div class="flex flex-col space-y-4 text-center md:text-left">
                <div><a href="#" class="hover:text-strongCyan">FAQs</a></div>
                <div><a href="#" class="hover:text-strongCyan">Contact Us</a></div>
              </div>
              <!-- Menu 2 -->
              <div class="flex flex-col space-y-4 text-center md:text-left">
                <div><a href="#" class="hover:text-strongCyan">Privacy Policy</a></div>
                <div><a href="#" class="hover:text-strongCyan">Press Kit</a></div>
              </div>
              <!-- Menu 3 -->
              <div class="flex flex-col space-y-4 text-center md:text-left">
                <div><a href="#" class="hover:text-cyan-800">Install Guide</a></div>
              </div>
            </div>

            <!-- Social Icons -->
            <div class="flex justify-between w-32 py-1">
              <a href="#"><img :src="'/storage/images/clipboard/icon-facebook.svg'" alt="" class="duration-200 ficon"/></a>
              <a href="#"><img :src="'/storage/images/clipboard/icon-twitter.svg'" alt="" class="duration-200 ficon"/></a>
              <a href="#"><img :src="'/storage/images/clipboard/icon-instagram.svg'" alt="" class="duration-200 ficon"/></a>
            </div>
          </div>
        </div>
      </div>
    </footer>


</template>
