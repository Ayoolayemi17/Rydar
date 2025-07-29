<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rydar - Smart Bike Rentals</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-800 font-sans">

  <!-- Hero Section -->
  <section class="bg-gradient-to-r from-green-500 to-blue-500 text-white py-20 text-center">
    <h1 class="text-5xl font-bold mb-4">Rydar</h1>
    <p class="text-xl mb-6">Smart, Affordable, and Eco-Friendly Bike Rentals for University Students</p>
    <a href="#signup" class="bg-white text-green-600 px-6 py-3 rounded-xl font-semibold hover:bg-gray-100">Get Started</a>
  </section>

  <!-- Features -->
  <section class="py-16 px-6 text-center">
    <h2 class="text-3xl font-bold mb-12">Why Choose Rydar?</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div class="bg-gray-100 p-6 rounded-xl shadow-md">
        <h3 class="text-xl font-semibold mb-4">🚲 Easy Rentals</h3>
        <p>Scan a QR code and unlock your bike instantly with our smart lock technology.</p>
      </div>
      <div class="bg-gray-100 p-6 rounded-xl shadow-md">
        <h3 class="text-xl font-semibold mb-4">💰 Affordable Pricing</h3>
        <p>Pay only for the time you ride. Perfect for students on a budget.</p>
      </div>
      <div class="bg-gray-100 p-6 rounded-xl shadow-md">
        <h3 class="text-xl font-semibold mb-4">🌱 Eco-Friendly</h3>
        <p>Reduce campus traffic and help the environment with our sustainable transport option.</p>
      </div>
    </div>
  </section>

  <!-- How It Works -->
  <section class="bg-gray-50 py-16 px-6 text-center">
    <h2 class="text-3xl font-bold mb-12">How It Works</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div>
        <div class="text-green-600 text-4xl mb-4">📱</div>
        <h3 class="font-semibold">1. Scan QR</h3>
        <p>Scan the bike’s QR code via the Rydar app or web.</p>
      </div>
      <div>
        <div class="text-blue-600 text-4xl mb-4">🔓</div>
        <h3 class="font-semibold">2. Unlock</h3>
        <p>Smart lock opens automatically. Start your ride.</p>
      </div>
      <div>
        <div class="text-yellow-500 text-4xl mb-4">✅</div>
        <h3 class="font-semibold">3. Return</h3>
        <p>Park and lock the bike when you’re done.</p>
      </div>
    </div>
  </section>

  <!-- Call to Action -->
  <section id="signup" class="py-20 text-center">
    <h2 class="text-3xl font-bold mb-6">Be the First to Ride</h2>
    <p class="mb-6 text-lg">Sign up to get early access when we launch on your campus.</p>
    <form class="flex flex-col md:flex-row justify-center items-center gap-4 max-w-md mx-auto">
      <input type="email" placeholder="Enter your email" required class="px-4 py-3 rounded-xl border border-gray-300 w-full">
      <button class="bg-green-600 text-white px-6 py-3 rounded-xl hover:bg-green-700">Notify Me</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white py-6 text-center">
    <p>&copy; 2025 Rydar. All rights reserved.</p>
  </footer>

</body>
</html>
