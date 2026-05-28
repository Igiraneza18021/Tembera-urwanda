<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-gray-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center mb-16">
        <div>
          <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">Kigali City</h1>
          <p class="text-xl text-gray-600 leading-relaxed mb-6">Rwanda's vibrant capital city blends modern development with rich cultural heritage, offering museums, markets, restaurants, and a thriving international community.</p>
          <div class="space-y-4">
            <div class="flex items-center gap-4">
              <span class="text-3xl">🏙️</span>
              <div>
                <h3 class="font-bold text-gray-800">Modern Infrastructure</h3>
                <p class="text-gray-600 text-sm">Clean, organized, and well-developed city</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">🍽️</span>
              <div>
                <h3 class="font-bold text-gray-800">World-Class Dining</h3>
                <p class="text-gray-600 text-sm">International and local cuisine</p>
              </div>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-3xl">🛍️</span>
              <div>
                <h3 class="font-bold text-gray-800">Shopping & Culture</h3>
                <p class="text-gray-600 text-sm">Markets, galleries, and cultural centers</p>
              </div>
            </div>
          </div>
        </div>
        <div class="bg-gradient-to-br from-purple-500 to-pink-600 rounded-xl h-96 flex items-center justify-center text-7xl shadow-lg">
          🏙️
        </div>
      </div>

      <!-- Top Attractions -->
      <div class="mb-16">
        <h2 class="text-4xl font-bold text-gray-800 mb-8 text-center">Top Attractions</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🕯️</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Genocide Memorial</h3>
            <p class="text-gray-600 mb-4">A powerful and moving tribute to the victims of the 1994 genocide, offering insights into Rwanda's painful history.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🎨</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Art & Culture</h3>
            <p class="text-gray-600 mb-4">Visit art galleries, craft markets, and cultural centers showcasing Rwanda's vibrant artistic traditions.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🍴</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Dining Scene</h3>
            <p class="text-gray-600 mb-4">Experience diverse cuisines from traditional Rwandan dishes to international fine dining establishments.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🏙️</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">City Tours</h3>
            <p class="text-gray-600 mb-4">Guided tours exploring the city's neighborhoods, landmarks, and local life with experienced city guides.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🛍️</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Shopping</h3>
            <p class="text-gray-600 mb-4">Browse local crafts, traditional textiles, and modern boutiques in Kigali's vibrant shopping districts.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
          <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition">
            <div class="text-5xl mb-4">🌳</div>
            <h3 class="text-2xl font-bold text-gray-800 mb-3">Parks & Nature</h3>
            <p class="text-gray-600 mb-4">Relax in urban parks and enjoy peaceful green spaces within the bustling city center.</p>
            <button class="text-green-600 font-semibold hover:text-green-700">Learn More →</button>
          </div>
        </div>
      </div>

      <!-- Practical Info -->
      <div class="bg-green-50 rounded-xl p-12">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Practical Information</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Population</p>
            <p class="text-lg font-bold text-green-600">~1.2M</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Altitude</p>
            <p class="text-lg font-bold text-green-600">1,567m</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Climate</p>
            <p class="text-lg font-bold text-green-600">Temperate</p>
          </div>
          <div class="text-center">
            <p class="text-sm text-gray-600 mb-2 uppercase font-semibold">Main Airport</p>
            <p class="text-lg font-bold text-green-600">10km Away</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>