<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-gray-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="text-center mb-16">
        <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">Gallery - Videos</h1>
        <p class="text-xl text-gray-600 max-w-2xl mx-auto">Cinematic footage showcasing Rwanda's beauty and culture</p>
      </div>

      <!-- Video Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-16">
        <!-- Video Cards -->
        <div v-for="i in 6" :key="i" class="group relative overflow-hidden rounded-xl shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="bg-gradient-to-br from-purple-500 to-pink-500 h-72 flex items-center justify-center text-7xl group-hover:scale-110 transition duration-300">
            🎥
          </div>
          <div class="absolute inset-0 bg-black bg-opacity-40 group-hover:bg-opacity-60 transition duration-300 flex items-center justify-center">
            <div class="w-16 h-16 bg-white rounded-full flex items-center justify-center group-hover:scale-125 transition duration-300">
              ▶
            </div>
          </div>
          <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black to-transparent p-4">
            <p class="text-white font-semibold">Video {{ i }}</p>
            <p class="text-gray-300 text-sm">Experience Rwanda</p>
          </div>
        </div>
      </div>

      <!-- Featured Video Section -->
      <div class="bg-white rounded-xl shadow-lg overflow-hidden mb-16">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 p-8">
          <div class="bg-gradient-to-br from-indigo-500 to-purple-600 h-80 rounded-lg flex items-center justify-center text-7xl">
            🎬
          </div>
          <div class="flex flex-col justify-center">
            <h2 class="text-3xl font-bold text-gray-800 mb-4">Featured: Journey Through Rwanda</h2>
            <p class="text-gray-600 mb-6 leading-relaxed">Embark on a visual journey through the stunning landscapes, vibrant culture, and unforgettable experiences that make Rwanda one of Africa's most captivating destinations.</p>
            <ul class="space-y-3 mb-8">
              <li class="flex items-start gap-3">
                <span class="text-green-600 text-2xl">✓</span>
                <span class="text-gray-700">Professional cinematography and production</span>
              </li>
              <li class="flex items-start gap-3">
                <span class="text-green-600 text-2xl">✓</span>
                <span class="text-gray-700">4K resolution for stunning visuals</span>
              </li>
              <li class="flex items-start gap-3">
                <span class="text-green-600 text-2xl">✓</span>
                <span class="text-gray-700">Authentic stories from local communities</span>
              </li>
            </ul>
            <button class="w-full md:w-auto px-8 py-3 bg-green-600 text-white rounded-lg font-semibold hover:bg-green-700 transition">Watch Now</button>
          </div>
        </div>
      </div>

      <!-- CTA -->
      <div class="text-center bg-green-50 rounded-xl p-12">
        <h2 class="text-3xl font-bold text-gray-800 mb-4">Subscribe to Our Channel</h2>
        <p class="text-gray-600 mb-6 max-w-2xl mx-auto">Get notified about new videos, travel guides, and exclusive content from Rwanda</p>
        <button class="px-8 py-3 bg-green-600 text-white rounded-lg font-semibold hover:bg-green-700 transition">Subscribe Now</button>
      </div>
    </div>
  </section>
</template>