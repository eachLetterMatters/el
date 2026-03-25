<template>
  <div class="min-h-screen bg-gradient-to-br from-gray-950 via-gray-900 to-gray-950 text-white">
    
    <!-- Navbar -->
    <nav class="fixed top-0 w-full z-50 backdrop-blur-md bg-black/30 border-b border-white/10">
      <div class="flex justify-between items-center p-5 max-w-5xl mx-auto">
        <h1 class="text-xl font-bold tracking-wide">norPS</h1>

        <div class="space-x-6 text-sm text-gray-300">
          <a href="#about" class="hover:text-white transition">O mnie</a>
          <a href="#projects" class="hover:text-white transition">Projekty</a>
          <a href="#contact" class="hover:text-white transition">Kontakt</a>
        </div>
      </div>
    </nav>

    <!-- Hero -->
    <section class="pt-40 text-center px-6">
      <h2 class="text-5xl md:text-7xl font-bold leading-tight">
        Cześć 👋
      </h2>

      <p class="mt-6 text-gray-400 text-lg md:text-xl max-w-xl mx-auto">
        Jestem frontend developerem i tworzę nowoczesne aplikacje w Vue.
      </p>

      <div class="mt-10 flex justify-center gap-4">
        <a href="#projects"
           class="px-6 py-3 rounded-xl bg-white text-black font-semibold hover:scale-105 transition">
          Zobacz projekty
        </a>

        <a href="#contact"
           class="px-6 py-3 rounded-xl border border-white/20 hover:bg-white/10 transition">
          Kontakt
        </a>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="mt-40 max-w-3xl mx-auto px-6">
      <h3 class="text-3xl font-semibold mb-6">O mnie</h3>
      <p class="text-gray-400 leading-relaxed text-lg">
        Uczę się tworzenia aplikacji webowych. Interesuję się frontendem, UI/UX
        i nowoczesnymi technologiami jak Vue, Vite i Tailwind CSS.
      </p>
    </section>

    <!-- Projects -->
    <section id="projects" class="mt-40 max-w-5xl mx-auto px-6">
      <h3 class="text-3xl font-semibold mb-10">Projekty</h3>

      <div class="grid md:grid-cols-2 gap-8">
        <div class="group bg-white/5 border border-white/10 p-6 rounded-2xl hover:bg-white/10 transition">
          <h4 class="text-xl font-bold mb-2 group-hover:translate-x-1 transition">
            Projekt 1
          </h4>
          <p class="text-gray-400">
            Opis projektu – co robi, jakie technologie itd.
          </p>
        </div>

        <div class="group bg-white/5 border border-white/10 p-6 rounded-2xl hover:bg-white/10 transition">
          <h4 class="text-xl font-bold mb-2 group-hover:translate-x-1 transition">
            Projekt 2
          </h4>
          <p class="text-gray-400">
            Opis projektu – co robi, jakie technologie itd.
          </p>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="mt-40 text-center px-6">
      <h3 class="text-3xl font-semibold mb-6">Kontakt</h3>

      <p class="text-gray-400">📧 twoj@email.com</p>

      <div class="mt-6 text-gray-500 text-sm">
        GitHub • LinkedIn • Discord
      </div>
    </section>

    <!-- Footer -->
    <footer class="mt-24 text-center text-gray-500 pb-10">
      © 2026 norPS
    </footer>
  </div>
</template>

<script setup>
</script>

<style>
html {
  scroll-behavior: smooth;
}
</style>