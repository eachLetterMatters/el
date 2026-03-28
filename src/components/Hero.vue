<template>
  <section class="relative w-full overflow-hidden min-h-screen flex items-center">
    <div
      class="w-full px-5 sm:px-8 md:px-12 lg:px-8 max-w-5xl lg:max-w-7xl mx-auto relative z-10"
    >
      <div class="grid lg:grid-cols-2 gap-10 xl:gap-14 items-center">

        <!-- LEFT -->
        <div class="flex flex-col md:mt-0 mt-20 justify-center">

          <div class="text-white lg:text-left" data-aos="fade-right">
            <h1 class="text-white font-bold text-4xl md:text-5xl lg:text-6xl leading-tight">
              cześć, jestem
              <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-cyan-400">
                Konrad
              </span>
            </h1>

            <p
              class="text-blue-200 font-medium text-lg md:text-xl mt-4"
              data-aos="fade-right"
              data-aos-delay="100"
            >
              Python/Java Developer
            </p>
          </div>

          <p
            class="text-gray-300 pt-6 text-center lg:text-left mx-auto max-w-xl text-lg leading-relaxed"
          >
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Facilis illo ducimus adipisci! Voluptatum odit aspernatur
            ab sint dolorem ipsa officia nam.
          </p>

          <!-- BUTTONS -->
          <div
            class="flex items-center gap-4 pt-8 flex-col sm:flex-row sm:w-max sm:mx-auto lg:mx-0"
            data-aos="fade-up"
            data-aos-delay="300"
          >
            <button
              class="px-8 md:px-10 py-4 rounded-xl relative group w-full sm:w-max flex justify-center overflow-hidden bg-gradient-to-r from-blue-600 to-cyan-600 hover:from-blue-500 hover:to-cyan-500 transition-all duration-300"
            >
              <span class="relative flex items-center justify-center text-white font-semibold text-lg">
                Skontaktuj się
              </span>

              <ArrowUturnRightIcon
                class="ml-2 w-5 h-5 text-white group-hover:translate-x-1 transition-transform"
              />
            </button>

            <button
              class="border-2 border-blue-400 px-8 md:px-10 py-4 rounded-xl relative group w-full sm:w-max flex justify-center hover:bg-blue-400/10 transition-all duration-300"
            >
              <div class="flex items-center justify-center gap-2">
                <ArrowDownTrayIcon
                  class="w-5 h-5 text-blue-400 group-hover:translate-y-1 transition-transform"
                />
                <span class="text-white">Pobierz CV</span>
              </div>
            </button>
          </div>

          <!-- STATS -->
          <div class="flex items-center justify-center lg:justify-start gap-8 pt-12"
            data-aos="fade-up"
            data-aos-delay="400">

		    <div class="text-center">
              <div class="text-2xl font-bold text-blue-400">3+</div>
              <div class="text-blue-200 text-sm">Lata nauki</div>
            </div>

            <div class="text-center">
              <div class="text-2xl font-bold text-blue-400">20+</div>
              <div class="text-blue-200 text-sm">Projekty</div>
            </div>

            <div class="text-center">
              <div class="text-2xl font-bold text-blue-400">100+</div>
              <div class="text-blue-200 text-sm">Commity</div>
            </div>
          </div>
        </div>

        <!-- RIGHT IMAGE -->
        <div class="lg:h-full flex justify-center lg:justify-end">
          <div class="relative w-full max-w-md lg:max-w-lg">

            <div
              class="relative z-10 bg-gradient-to-r from-blue-600 to-cyan-600 shadow-2xl
              rounded-[50%_40%_30%_60%/60%_30%_70%_30%] p-4 backdrop-blur-sm
              border border-blue-500/30 -translate-y-6"
              data-aos="zoom-in"
              data-aos-delay="500"
            >
              <div class="rounded-xl overflow-hidden">
                <img
                  src="/pic.png"
                  alt="hero image"
                  loading="lazy"
                  class="w-[500px] h-[500px] rounded-full object-contain -translate-y-6 mx-auto"
                />
              </div>
            </div>

            <div
              class="absolute -top-2 -right-4 w-10 h-10 bg-blue-400 rounded-full blur-sm opacity-60 animate-pulse"
            ></div>

          </div>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
import { ArrowDownTrayIcon, ArrowUturnRightIcon } from '@heroicons/vue/24/solid'

export default {
  name: "HeroSection",
  components: {
    ArrowDownTrayIcon,
    ArrowUturnRightIcon
  }
}
</script>

<style></style>