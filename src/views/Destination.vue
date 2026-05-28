<template>
    <section class="min-h-screen bg-gradient-to-b from-white to-gray-50 py-20 px-4">
        <div class="max-w-6xl mx-auto">
            <!-- Header -->
            <div class="text-center mb-16">
                <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">Explore Our Destinations</h1>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Each destination offers unique experiences and breathtaking natural beauty</p>
            </div>

            <!-- Destination Cards -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Volcanoes National Park -->
                <div class="bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
                    <div class="h-48 bg-gradient-to-br from-red-600 to-orange-500 flex items-center justify-center text-6xl">
                        🏔️
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Volcanoes National Park</h3>
                        <p class="text-gray-600 mb-4">Home to the endangered mountain gorillas and stunning volcanic peaks</p>
                        <div class="space-y-2 mb-6">
                            <p class="text-sm text-gray-600"><strong>Best Time:</strong> June-September, December-January</p>
                            <p class="text-sm text-gray-600"><strong>Altitude:</strong> 2,400-4,507m</p>
                            <p class="text-sm text-gray-600"><strong>Highlights:</strong> Gorilla trekking, volcanic scenery</p>
                        </div>
                        <button class="w-full bg-green-600 text-white py-2 rounded-lg font-semibold hover:bg-green-700 transition">
                            Learn More
                        </button>
                    </div>
                </div>

                <!-- Nyungwe National Park -->
                <div class="bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
                    <div class="h-48 bg-gradient-to-br from-green-700 to-teal-600 flex items-center justify-center text-6xl">
                        🌳
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Nyungwe National Park</h3>
                        <p class="text-gray-600 mb-4">Ancient tropical rainforest with incredible biodiversity</p>
                        <div class="space-y-2 mb-6">
                            <p class="text-sm text-gray-600"><strong>Best Time:</strong> Year-round accessible</p>
                            <p class="text-sm text-gray-600"><strong>Area:</strong> 970 square kilometers</p>
                            <p class="text-sm text-gray-600"><strong>Highlights:</strong> Canopy walks, chimpanzees</p>
                        </div>
                        <button class="w-full bg-green-600 text-white py-2 rounded-lg font-semibold hover:bg-green-700 transition">
                            Learn More
                        </button>
                    </div>
                </div>

                <!-- Akagera National Park -->
                <div class="bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
                    <div class="h-48 bg-gradient-to-br from-yellow-600 to-amber-500 flex items-center justify-center text-6xl">
                        🦁
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Akagera National Park</h3>
                        <p class="text-gray-600 mb-4">Rwanda's largest savanna with the Big Five wildlife</p>
                        <div class="space-y-2 mb-6">
                            <p class="text-sm text-gray-600"><strong>Best Time:</strong> June-September</p>
                            <p class="text-sm text-gray-600"><strong>Area:</strong> 1,122 square kilometers</p>
                            <p class="text-sm text-gray-600"><strong>Highlights:</strong> Safari, Big Five</p>
                        </div>
                        <button class="w-full bg-green-600 text-white py-2 rounded-lg font-semibold hover:bg-green-700 transition">
                            Learn More
                        </button>
                    </div>
                </div>

                <!-- Lake Kivu -->
                <div class="bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
                    <div class="h-48 bg-gradient-to-br from-blue-500 to-cyan-400 flex items-center justify-center text-6xl">
                        💧
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Lake Kivu</h3>
                        <p class="text-gray-600 mb-4">Beautiful freshwater lake perfect for relaxation and water activities</p>
                        <div class="space-y-2 mb-6">
                            <p class="text-sm text-gray-600"><strong>Location:</strong> Western Rwanda</p>
                            <p class="text-sm text-gray-600"><strong>Water Temp:</strong> 23-25°C</p>
                            <p class="text-sm text-gray-600"><strong>Highlights:</strong> Swimming, kayaking, beach resorts</p>
                        </div>
                        <button class="w-full bg-green-600 text-white py-2 rounded-lg font-semibold hover:bg-green-700 transition">
                            Learn More
                        </button>
                    </div>
                </div>

                <!-- Kigali City -->
                <div class="bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
                    <div class="h-48 bg-gradient-to-br from-purple-600 to-pink-500 flex items-center justify-center text-6xl">
                        🏙️
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Kigali City</h3>
                        <p class="text-gray-600 mb-4">Modern capital city blending culture, history, and urban amenities</p>
                        <div class="space-y-2 mb-6">
                            <p class="text-sm text-gray-600"><strong>Population:</strong> ~1.2 million</p>
                            <p class="text-sm text-gray-600"><strong>Altitude:</strong> 1,567m</p>
                            <p class="text-sm text-gray-600"><strong>Highlights:</strong> Museums, markets, restaurants</p>
                        </div>
                        <button class="w-full bg-green-600 text-white py-2 rounded-lg font-semibold hover:bg-green-700 transition">
                            Learn More
                        </button>
                    </div>
                </div>

                <!-- Ruhengeri (Musanze) -->
                <div class="bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition transform hover:-translate-y-2">
                    <div class="h-48 bg-gradient-to-br from-indigo-600 to-blue-500 flex items-center justify-center text-6xl">
                        🏞️
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Musanze (Ruhengeri)</h3>
                        <p class="text-gray-600 mb-4">Gateway to Volcanoes with charming mountain town atmosphere</p>
                        <div class="space-y-2 mb-6">
                            <p class="text-sm text-gray-600"><strong>Location:</strong> Northern Rwanda</p>
                            <p class="text-sm text-gray-600"><strong>Altitude:</strong> 1,800m</p>
                            <p class="text-sm text-gray-600"><strong>Highlights:</strong> Base for trekking, local culture</p>
                        </div>
                        <button class="w-full bg-green-600 text-white py-2 rounded-lg font-semibold hover:bg-green-700 transition">
                            Learn More
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>