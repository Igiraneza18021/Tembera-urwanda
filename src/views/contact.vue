<template>
    <section class="min-h-screen bg-gradient-to-b from-white to-gray-50 py-20 px-4">
        <div class="max-w-6xl mx-auto">
            <!-- Header -->
            <div class="text-center mb-16">
                <h1 class="text-5xl md:text-6xl font-bold text-gray-800 mb-6">Get In Touch</h1>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Have questions? We'd love to hear from you. Reach out to us anytime.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
                <!-- Contact Info Cards -->
                <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition text-center">
                    <div class="text-4xl mb-4">📍</div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Location</h3>
                    <p class="text-gray-600">Kigali, Rwanda</p>
                    <p class="text-gray-600">East Africa</p>
                </div>
                <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition text-center">
                    <div class="text-4xl mb-4">📧</div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Email</h3>
                    <p class="text-gray-600">info@temberaurwanda.com</p>
                    <p class="text-gray-600">support@temberaurwanda.com</p>
                </div>
                <div class="bg-white rounded-lg p-8 shadow-md hover:shadow-lg transition text-center">
                    <div class="text-4xl mb-4">📞</div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Phone</h3>
                    <p class="text-gray-600">+250 123 456 789</p>
                    <p class="text-gray-600">Available 24/7</p>
                </div>
            </div>

            <!-- Contact Form -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <div class="bg-white rounded-xl shadow-lg p-8">
                    <h2 class="text-2xl font-bold text-gray-800 mb-6">Send us a Message</h2>
                    <form class="space-y-6">
                        <div>
                            <label class="block text-gray-700 font-semibold mb-2">Full Name</label>
                            <input type="text" placeholder="Enter your name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-green-600">
                        </div>
                        <div>
                            <label class="block text-gray-700 font-semibold mb-2">Email Address</label>
                            <input type="email" placeholder="Enter your email" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-green-600">
                        </div>
                        <div>
                            <label class="block text-gray-700 font-semibold mb-2">Subject</label>
                            <input type="text" placeholder="What is this about?" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-green-600">
                        </div>
                        <div>
                            <label class="block text-gray-700 font-semibold mb-2">Message</label>
                            <textarea placeholder="Tell us your message..." rows="5" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-green-600"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-green-600 text-white py-3 rounded-lg font-semibold hover:bg-green-700 transition">
                            Send Message
                        </button>
                    </form>
                </div>

                <!-- Contact Info & Hours -->
                <div>
                    <div class="bg-gradient-to-br from-green-600 to-emerald-500 rounded-xl p-8 text-white mb-8">
                        <h2 class="text-2xl font-bold mb-6">Business Hours</h2>
                        <div class="space-y-3">
                            <div class="flex justify-between">
                                <span>Monday - Friday</span>
                                <span class="font-semibold">8:00 AM - 6:00 PM</span>
                            </div>
                            <div class="flex justify-between">
                                <span>Saturday</span>
                                <span class="font-semibold">9:00 AM - 4:00 PM</span>
                            </div>
                            <div class="flex justify-between">
                                <span>Sunday</span>
                                <span class="font-semibold">10:00 AM - 2:00 PM</span>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-8 shadow-lg">
                        <h2 class="text-2xl font-bold text-gray-800 mb-6">Why Contact Us?</h2>
                        <ul class="space-y-4">
                            <li class="flex items-start">
                                <span class="text-green-600 font-bold mr-3">✓</span>
                                <span class="text-gray-700">Expert travel advice and recommendations</span>
                            </li>
                            <li class="flex items-start">
                                <span class="text-green-600 font-bold mr-3">✓</span>
                                <span class="text-gray-700">Personalized tour planning</span>
                            </li>
                            <li class="flex items-start">
                                <span class="text-green-600 font-bold mr-3">✓</span>
                                <span class="text-gray-700">Best price guarantees</span>
                            </li>
                            <li class="flex items-start">
                                <span class="text-green-600 font-bold mr-3">✓</span>
                                <span class="text-gray-700">24/7 customer support</span>
                            </li>
                            <li class="flex items-start">
                                <span class="text-green-600 font-bold mr-3">✓</span>
                                <span class="text-gray-700">Unforgettable experiences guaranteed</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>