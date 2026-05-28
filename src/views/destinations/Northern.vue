<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-gray-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">Northern Rwanda</h1>
          <p class="text-xl text-gray-600 leading-relaxed mb-6">Home to the iconic Volcanoes National Park and the magnificent mountain gorillas, Northern Rwanda is a paradise for nature lovers and adventure seekers.</p>
          <div class="space-y-4">
            <div class="flex items-center gap-4">
              <span class="text-3xl">🏔️</span>
              <div>
                <h3 class="font-bold text-gray-800">Volcanoes National Park</h3>
                <p class="text-gray-600 text-sm">Gorilla trekking and volcanic scenery</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">🌿</span>
              <div>
                <h3 class="font-bold text-gray-800">Pristine Forests</h3>
                <p class="text-gray-600 text-sm">Rich biodiversity and endemic species</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">❄️</span>
              <div>
                <h3 class="font-bold text-gray-800">Mountain Climate</h3>
                <p class="text-gray-600 text-sm">Cool temperatures and misty landscapes</p>
              </div>
            </div>
          </div>
        </div>
        <div class="bg-gradient-to-br from-red-400 to-orange-500 rounded-xl h-96 flex items-center justify-center text-7xl shadow-lg">
          ⛰️
        </div>
      </div>

      <!-- Activities -->
      <div class="mb-16">
        <h2 class="text-4xl font-bold text-gray-800 mb-8 text-center">Must-Do Activities</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🦍</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Gorilla Trekking</h3>
            <p class="text-gray-600 mb-4">Experience an unforgettable encounter with mountain gorillas in their natural habitat. The most sought-after wildlife experience in Africa.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🥾</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Hiking Trails</h3>
            <p class="text-gray-600 mb-4">Explore multiple hiking routes including summits of volcanic cones with stunning panoramic views of the landscape.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">📸</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Photography Tours</h3>
            <p class="text-gray-600 mb-4">Capture stunning images of mountain gorillas, landscape vistas, and unique wildlife with expert photographer guides.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
        </div>
      </div>

      <!-- Practical Info -->
      <div class="bg-green-50 rounded-xl p-12">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Practical Information</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Best Time to Visit</p>
            <p class="text-lg font-bold text-green-600">June-Sept, Dec-Jan</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Altitude</p>
            <p class="text-lg font-bold text-green-600">2,400 - 4,507m</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Temperature</p>
            <p class="text-lg font-bold text-green-600">10-20°C</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Distance from Kigali</p>
            <p class="text-lg font-bold text-green-600">~100km</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>