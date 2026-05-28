<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-gray-50 py-20 px-4">
    <div class="max-w-6xl mx-auto">
      <!-- Header -->
      <div class="text-center mb-16">
        <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">Gallery - Photos</h1>
        <p class="text-xl text-gray-600 max-w-2xl mx-auto">Stunning photography from Rwanda's most beautiful locations</p>
      </div>

      <!-- Photo Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
        <!-- Photo Cards -->
        <div v-for="i in 9" :key="i" class="group relative overflow-hidden rounded-lg shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
          <div class="bg-gradient-to-br from-green-400 to-blue-500 h-64 flex items-center justify-center text-6xl group-hover:scale-110 transition duration-300">
            📸
          </div>
          <div class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-40 transition duration-300 flex items-center justify-center">
            <button class="opacity-0 group-hover:opacity-100 transition px-6 py-2 bg-white text-green-600 rounded-lg font-semibold">View</button>
          </div>
        </div>
      </div>

      <!-- CTA -->
      <div class="text-center bg-green-50 rounded-xl p-12">
        <h2 class="text-3xl font-bold text-gray-800 mb-4">Want to Share Your Photos?</h2>
        <p class="text-gray-600 mb-6 max-w-2xl mx-auto">Upload your best Rwanda travel photos and be featured in our gallery</p>
        <button class="px-8 py-3 bg-green-600 text-white rounded-lg font-semibold hover:bg-green-700 transition">Submit Your Photos</button>
      </div>
    </div>
  </section>
</template>