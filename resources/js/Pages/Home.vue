<template>
  <div class="min-h-screen scroll-smooth  bg-gradient-to-b from-gray-50 via-white to-gray-50 text-gray-800 antialiased">
	<Navbar />
    <!-- HERO -->
    	<section class="relative scroll-smooth  bg-gradient-to-r from-blue-600 to-cyan-500 text-white py-32 overflow-hidden">

  <div class="absolute inset-0 opacity-20">
    <div class="w-[600px] h-[600px] bg-white rounded-full blur-3xl absolute -top-40 -left-40"></div>
    <div class="w-[500px] h-[500px] bg-cyan-300 rounded-full blur-3xl absolute bottom-0 right-0"></div>
  </div>

  <div class="relative max-w-6xl mx-auto px-6 text-center">

    <h1 class="text-5xl md:text-6xl font-extrabold mb-6 leading-tight">
      Cleaning Services <br> <span class="text-cyan-200">Professionnels</span>
    </h1>

    <p class="text-lg md:text-xl text-white/90 mb-10">
      Nous transformons vos espaces en environnements propres, sains et modernes
    </p>

    <div class="flex justify-center gap-4">
      <a href="#contact"
   class="bg-white/90 backdrop-blur text-blue-600 px-6 py-3 rounded-xl font-semibold
          hover:scale-105 hover:bg-white transition duration-300 shadow-lg">
  Devis gratuit
</a>

      <a href="#services" class="border border-white px-6 py-3 rounded-xl hover:bg-white hover:text-blue-600 transition">
        Nos services
      </a>
    </div>

  </div>
</section>
<section class="py-12 bg-white">
  <div class="max-w-6xl mx-auto px-6">

    <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">

      <div>
        <h3 class="text-4xl font-bold text-blue-600">500+</h3>
        <p class="text-gray-600">Clients satisfaits</p>
      </div>

      <div>
        <h3 class="text-4xl font-bold text-blue-600">10+</h3>
        <p class="text-gray-600">Années d'expérience</p>
      </div>

      <div>
        <h3 class="text-4xl font-bold text-blue-600">24/7</h3>
        <p class="text-gray-600">Support client</p>
      </div>

      <div>
        <h3 class="text-4xl font-bold text-blue-600">100%</h3>
        <p class="text-gray-600">Satisfaction</p>
      </div>

    </div>

  </div>
</section>
    <!-- SERVICES -->
    <section id="services" class="py-24 max-w-6xl mx-auto px-6 scroll-smooth ">

  <h2 class="text-4xl md:text-5xl font-extrabold text-center mb-16 tracking-tight">
    Nos Services
  </h2>

  <div class="grid md:grid-cols-3 gap-8">

    <div class="bg-white/80 backdrop-blur-xl p-8 rounded-2xl shadow-sm border border-gray-100
            transition duration-300 hover:-translate-y-2 hover:shadow-2xl hover:scale-[1.03]">
<div class="w-12 h-1 bg-blue-500 rounded mb-4"></div>

   <House class="w-10 h-10 text-blue-500 mb-4" />
    <h3 class="text-xl font-bold mb-3">Maison</h3>
      <p class="text-gray-600">Nettoyage complet de votre domicile avec soin et précision.</p>
    </div>

    <div class="bg-white/80 backdrop-blur-xl p-8 rounded-2xl shadow-sm border border-gray-100
            transition duration-300 hover:-translate-y-2 hover:shadow-2xl hover:scale-[1.03]">
<div class="w-12 h-1 bg-blue-500 rounded mb-4"></div>
      <Building2 class="w-10 h-10 text-blue-500 mb-4" />
        <h3 class="text-xl font-bold mb-3">Bureau</h3>
      <p class="text-gray-600">Espaces de travail propres pour plus de productivité.</p>
    </div>

    <div class="bg-white/80 backdrop-blur-xl p-8 rounded-2xl shadow-sm border border-gray-100
            transition duration-300 hover:-translate-y-2 hover:shadow-2xl hover:scale-[1.03]">
<div class="w-12 h-1 bg-blue-500 rounded mb-4"></div>
      <Sparkles class="w-10 h-10 text-blue-500 mb-4" />
<h3 class="text-xl font-bold mb-3">Deep Clean</h3>
      <p class="text-gray-600">Nettoyage en profondeur pour un résultat impeccable.</p>
    </div>

  </div>
</section>

<section class="bg-gray-100 py-24">
  <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">

    <div>
    <h2 class="text-4xl font-extrabold mb-8 tracking-tight">Pourquoi nous choisir ?</h2>


      <ul class="space-y-4 text-gray-700">
        <li>✔ Équipe professionnelle et expérimentée</li>
        <li>✔ Produits écologiques</li>
        <li>✔ Service rapide et fiable</li>
        <li>✔ Prix compétitifs</li>
      </ul>
    </div>

    <div class="bg-white p-8 rounded-2xl shadow-xl border border-gray-100 hover:scale-[1.02] transition duration-300">
      <p class="text-gray-600 italic">
        “Un service impeccable, rapide et très professionnel.”
      </p>
      <div class="mt-4 font-semibold">— Client satisfait</div>
    </div>

  </div>
</section>

    <!-- CONTACT -->
    <section id="contact" class="bg-gray-100 py-20  scroll-smooth ">
      <div class="max-w-3xl mx-auto text-center px-6">
        <h2 class="text-4xl md:text-5xl font-extrabold text-center mb-16 tracking-tight">Contactez-nous</h2>

        <p class="mb-6">Nous vous répondons rapidement pour un devis gratuit.</p>


        <input
        class="w-full p-4 mb-4 border border-gray-200 rounded-xl focus:ring-2 focus:ring-blue-500 focus:outline-none"
        placeholder="Votre email"
        />
       <textarea
        class="w-full p-4 mb-4 border border-gray-200 rounded-xl focus:ring-2 focus:ring-blue-500 focus:outline-none"
        rows="5"
        placeholder="Votre message"
        ></textarea>

        <button
        class="bg-blue-600 text-white px-8 py-4 rounded-xl shadow-lg hover:bg-blue-700 hover:scale-105 transition duration-300"
        >
          Envoyer
        </button>
      </div>
    </section>

  </div>
  <footer class="bg-gray-900 text-white py-12">
  <div class="max-w-6xl mx-auto px-6">

    <div class="grid md:grid-cols-3 gap-8">

      <div>
        <h3 class="text-xl font-bold mb-4">CleanPro</h3>
        <p class="text-gray-400">
          Services de nettoyage professionnels pour particuliers et entreprises.
        </p>
      </div>

      <div>
        <h3 class="text-xl font-bold mb-4">Contact</h3>
        <p class="text-gray-400">contact@cleanpro.com</p>
        <p class="text-gray-400">+213 555 00 00 00</p>
      </div>

      <div>
        <h3 class="text-xl font-bold mb-4">Horaires</h3>
        <p class="text-gray-400">Lun - Sam : 08h00 - 18h00</p>
      </div>

    </div>

    <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-500">
      © 2026 CleanPro. Tous droits réservés.
    </div>

  </div>
</footer>
</template>
<script setup>
import Navbar from '@/Components/Navbar.vue'
import { House, Building2, Sparkles } from '@lucide/vue'
</script>
