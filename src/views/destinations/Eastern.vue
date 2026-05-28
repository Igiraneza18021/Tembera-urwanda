<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-gray-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">Eastern Rwanda</h1>
          <p class="text-xl text-gray-600 leading-relaxed mb-6">Experience the wild heart of East Africa at Akagera National Park, Rwanda's largest protected savanna with the Big Five and pristine wilderness.</p>
          <div class="space-y-4">
            <div class="flex items-center gap-4">
              <span class="text-3xl">🦁</span>
              <div>
                <h3 class="font-bold text-gray-800">Big Five Safari</h3>
                <p class="text-gray-600 text-sm">Lions, leopards, elephants, buffalo, rhinos</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">🌄</span>
              <div>
                <h3 class="font-bold text-gray-800">Savanna Landscapes</h3>
                <p class="text-gray-600 text-sm">Rolling grasslands and scenic vistas</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">🦓</span>
              <div>
                <h3 class="font-bold text-gray-800">Wildlife Abundance</h3>
                <p class="text-gray-600 text-sm">Over 500+ animal species</p>
              </div>
            </div>
          </div>
        </div>
        <div class="bg-gradient-to-br from-yellow-400 to-orange-600 rounded-xl h-96 flex items-center justify-center text-7xl shadow-lg">
          🦁
        </div>
      </div>

      <!-- Activities -->
      <div class="mb-16">
        <h2 class="text-4xl font-bold text-gray-800 mb-8 text-center">Must-Do Activities</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🚙</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Game Drives</h3>
            <p class="text-gray-600 mb-4">Thrilling safari experiences with expert guides to spot Africa's most iconic wildlife in their natural habitat.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🌅</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Sunrise Safaris</h3>
            <p class="text-gray-600 mb-4">Witness the African dawn and observe wildlife during their most active hours on exclusive sunrise safari tours.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🛶</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">River Cruises</h3>
            <p class="text-gray-600 mb-4">Scenic boat cruises on the Kagera River offering unique perspectives of wildlife and riverside ecosystems.</p>
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
            <p class="text-lg font-bold text-green-600">June-Sept</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Park Size</p>
            <p class="text-lg font-bold text-green-600">1,122 km²</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Temperature</p>
            <p class="text-lg font-bold text-green-600">22-30°C</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Distance from Kigali</p>
            <p class="text-lg font-bold text-green-600">~140km</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>