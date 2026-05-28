<template>
  <footer class="bg-gradient-to-r from-green-800 to-green-900 text-white px-8 py-16 mt-16 shadow-2xl">
    <!-- Main container for the 4 sections in a row -->
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 text-left mb-12 max-w-7xl mx-auto">
      
      <!-- Section 2: Brand Logo & Tagline -->
      <div class="flex flex-col justify-center items-center lg:items-start text-center lg:text-left">
        <h3 class="text-4xl font-extrabold tracking-tighter text-white mb-2">
          TEMBERA<br />URWANDA
        </h3>
        <p class="text-sm text-green-200 mb-4">Discover the Land of a Thousand Hills</p>
        <div class="flex gap-4 justify-center lg:justify-start">
          <a href="#" class="w-10 h-10 bg-green-600 rounded-full flex items-center justify-center hover:bg-yellow-400 transition" aria-label="Facebook">f</a>
          <a href="#" class="w-10 h-10 bg-green-600 rounded-full flex items-center justify-center hover:bg-yellow-400 transition" aria-label="Twitter">t</a>
          <a href="#" class="w-10 h-10 bg-green-600 rounded-full flex items-center justify-center hover:bg-yellow-400 transition" aria-label="LinkedIn">in</a>
        </div>
      </div>

      <!-- Section 1: Quick Links (Site Map) -->
      <div>
        <h4 class="font-bold text-lg mb-6 uppercase tracking-wider border-b-2 border-yellow-400 pb-3">Quick Links</h4>
        <ul class="space-y-3 text-sm text-green-100">
          <li>
            <router-link to="/" class="hover:text-yellow-300 transition duration-300 font-semibold">↳ Home</router-link>
          </li>
          <li>
            <router-link to="/about" class="hover:text-yellow-300 transition duration-300 font-semibold">↳ About Rwanda</router-link>
          </li>
          <li>
            <router-link to="/services" class="hover:text-yellow-300 transition duration-300 font-semibold">↳ Services</router-link>
          </li>
          <li>
            <router-link to="/contacts" class="hover:text-yellow-300 transition duration-300 font-semibold">↳ Contacts</router-link>
          </li>
        </ul>
      </div>

      <!-- Section 3: Top Destinations -->
      <div>
        <h4 class="font-bold text-lg mb-6 uppercase tracking-wider border-b-2 border-yellow-400 pb-3">Top Destinations</h4>
        <ul class="space-y-3 text-sm text-green-100">
          <li><a href="#" class="hover:text-yellow-300 transition duration-300 font-semibold">🏔️ Volcanoes National Park</a></li>
          <li><a href="#" class="hover:text-yellow-300 transition duration-300 font-semibold">🌿 Nyungwe National Park</a></li>
          <li><a href="#" class="hover:text-yellow-300 transition duration-300 font-semibold">🦁 Akagera National Park</a></li>
          <li><a href="#" class="hover:text-yellow-300 transition duration-300 font-semibold">🏖️ Lake Kivu</a></li>
        </ul>
      </div>

      <!-- Section 4: Contact Information -->
      <div>
        <h4 class="font-bold text-lg mb-6 uppercase tracking-wider border-b-2 border-yellow-400 pb-3">Contact Info</h4>
        <ul class="space-y-3 text-sm text-green-100">
          <li class="flex items-start gap-3">
            <span class="text-yellow-400" aria-hidden="true">📍</span> <span>Gacuriro, Kigali, Rwanda</span>
          </li>
          <li class="flex items-start gap-3">
            <span class="text-yellow-400" aria-hidden="true">✉️</span> <span>info@temberaurwanda.com</span>
          </li>
          <li class="flex items-start gap-3">
            <span class="text-yellow-400" aria-hidden="true">📱</span> <span>+250 123 456 789</span>
          </li>
          <li class="flex items-start gap-3">
            <span class="text-yellow-400" aria-hidden="true">🕐</span> <span>24/7 Support</span>
          </li>
        </ul>
      </div>
    </div>

    <!-- Divider Line -->
    <div class="border-t border-green-700 my-8 max-w-7xl mx-auto"></div>

    <!-- Bottom Copyright & Links -->
    <div class="max-w-7xl mx-auto">
      <div class="flex flex-col md:flex-row justify-between items-center text-center md:text-left gap-6 text-sm text-green-200">
        <p>&copy; 2026 Tembera Urwanda. All rights reserved.</p>
        <div class="flex gap-6">
          <a href="#" class="hover:text-yellow-300 transition">Privacy Policy</a>
          <a href="#" class="hover:text-yellow-300 transition">Terms & Conditions</a>
          <a href="#" class="hover:text-yellow-300 transition">Sitemap</a>
        </div>
      </div>
    </div>
  </footer>
</template>
