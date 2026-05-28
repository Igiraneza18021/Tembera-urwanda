<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-gray-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">Southern Rwanda</h1>
          <p class="text-xl text-gray-600 leading-relaxed mb-6">Discover the lush tea plantations, stunning Nyungwe Forest, and the beautiful shores of Lake Kivu in Rwanda's verdant south.</p>
          <div class="space-y-4">
            <div class="flex items-center gap-4">
              <span class="text-3xl">🌿</span>
              <div>
                <h3 class="font-bold text-gray-800">Nyungwe Forest</h3>
                <p class="text-gray-600 text-sm">Ancient rainforest with incredible wildlife</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">☕</span>
              <div>
                <h3 class="font-bold text-gray-800">Tea Plantations</h3>
                <p class="text-gray-600 text-sm">Rolling hills covered in vibrant green tea</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">🏖️</span>
              <div>
                <h3 class="font-bold text-gray-800">Lake Kivu</h3>
                <p class="text-gray-600 text-sm">Africa's deepest lake with beach resorts</p>
              </div>
            </div>
          </div>
        </div>
        <div class="bg-gradient-to-br from-green-400 to-teal-600 rounded-xl h-96 flex items-center justify-center text-7xl shadow-lg">
          🌳
        </div>
      </div>

      <!-- Activities -->
      <div class="mb-16">
        <h2 class="text-4xl font-bold text-gray-800 mb-8 text-center">Must-Do Activities</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🌉</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Canopy Walks</h3>
            <p class="text-gray-600 mb-4">Experience the Nyungwe Forest from above with thrilling canopy walks and tree-top bridges offering unique perspectives.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🚣</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Lake Activities</h3>
            <p class="text-gray-600 mb-4">Enjoy swimming, kayaking, water sports, and relaxing beach time on the shores of beautiful Lake Kivu.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🐵</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Chimp Trekking</h3>
            <p class="text-gray-600 mb-4">Trek through Nyungwe Forest to encounter chimpanzees and other primates in their natural habitat.</p>
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
            <p class="text-lg font-bold text-green-600">Year-round</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Altitude</p>
            <p class="text-lg font-bold text-green-600">1,600 - 2,950m</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Temperature</p>
            <p class="text-lg font-bold text-green-600">18-25°C</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Distance from Kigali</p>
            <p class="text-lg font-bold text-green-600">~200km</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>