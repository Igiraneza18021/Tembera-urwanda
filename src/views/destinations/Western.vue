<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-gray-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">Western Rwanda</h1>
          <p class="text-xl text-gray-600 leading-relaxed mb-6">Explore the tranquil shores of Lake Kivu and the historic towns that echo Rwanda's journey to peace and reconciliation.</p>
          <div class="space-y-4">
            <div class="flex items-center gap-4">
              <span class="text-3xl">💎</span>
              <div>
                <h3 class="font-bold text-gray-800">Lake Kivu</h3>
                <p class="text-gray-600 text-sm">Africa's most beautiful freshwater lake</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">🏖️</span>
              <div>
                <h3 class="font-bold text-gray-800">Beach Resorts</h3>
                <p class="text-gray-600 text-sm">Luxury waterfront accommodations</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">🙏</span>
              <div>
                <h3 class="font-bold text-gray-800">Cultural Heritage</h3>
                <p class="text-gray-600 text-sm">Museums and reconciliation sites</p>
              </div>
            </div>
          </div>
        </div>
        <div class="bg-gradient-to-br from-blue-400 to-cyan-500 rounded-xl h-96 flex items-center justify-center text-7xl shadow-lg">
          💧
        </div>
      </div>

      <!-- Activities -->
      <div class="mb-16">
        <h2 class="text-4xl font-bold text-gray-800 mb-8 text-center">Must-Do Activities</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🚣</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Water Sports</h3>
            <p class="text-gray-600 mb-4">Kayaking, swimming, and water sports on the pristine waters of Lake Kivu with professional instructors.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🌅</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Sunset Cruises</h3>
            <p class="text-gray-600 mb-4">Romantic boat cruises across the lake during sunset with stunning views and local refreshments.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🏛️</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Cultural Tours</h3>
            <p class="text-gray-600 mb-4">Visit historical sites, peace memorials, and local communities to understand Rwanda's remarkable journey.</p>
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
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Lake Area</p>
            <p class="text-lg font-bold text-green-600">2,700 km²</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Water Temp</p>
            <p class="text-lg font-bold text-green-600">23-25°C</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Distance from Kigali</p>
            <p class="text-lg font-bold text-green-600">~300km</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>