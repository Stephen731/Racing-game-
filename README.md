# Racing-game-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Racing Game</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/alpinejs" defer></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet" />
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  <style>
    html { scroll-behavior: smooth; }
    body { font-family: 'Roboto', sans-serif; }
  </style>
</head>
<body class="bg-gray-900 text-white">

  <!-- Navigation Bar -->
  <nav class="bg-gray-800 p-4" x-data="{ open: false }">
    <div class="container mx-auto px-4 flex justify-between items-center">
      <a href="#" class="text-2xl font-bold">RacingGame</a>
      <div class="hidden md:flex space-x-4">
        <a href="#home" class="hover:text-gray-400">Home</a>
        <a href="#features" class="hover:text-gray-400">Features</a>
        <a href="#about" class="hover:text-gray-400">About</a>
        <a href="#contact" class="hover:text-gray-400">Contact</a>
      </div>
      <div class="md:hidden">
        <button @click="open = !open">
          <i class="fas fa-bars text-white text-xl"></i>
        </button>
      </div>
    </div>
    <div x-show="open" class="md:hidden px-4 pt-2 pb-4 space-y-2">
      <a href="#home" class="block hover:text-gray-400">Home</a>
      <a href="#features" class="block hover:text-gray-400">Features</a>
      <a href="#about" class="block hover:text-gray-400">About</a>
      <a href="#contact" class="block hover:text-gray-400">Contact</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="bg-gray-700 py-20">
    <div class="container mx-auto px-4 text-center" data-aos="zoom-in">
      <h1 class="text-5xl font-bold mb-4">Welcome to RacingGame</h1>
      <p class="text-xl mb-8">Experience the thrill of high-speed racing!</p>
      <a href="#" class="bg-blue-500 text-white px-6 py-3 rounded-full hover:bg-blue-600">Get Started</a>
    </div>
  </section>

  <!-- Features -->
  <section id="features" class="py-20">
    <div class="container mx-auto px-4">
      <h2 class="text-4xl font-bold text-center mb-12" data-aos="fade-up">Game Features</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Feature Item 1 -->
        <div class="bg-gray-800 p-6 rounded-lg" data-aos="fade-right">
          <img loading="lazy" src="https://storage.googleapis.com/a1aa/image/HIE5HJabm5EUae4hOau-Y7yA-scZeLwyHzHzqaO713o.jpg" alt="High-speed car" class="mb-4 rounded" width="400" height="300">
          <h3 class="text-2xl font-bold mb-2">High-Speed Racing</h3>
          <p>Experience the thrill of high-speed racing with realistic graphics and physics.</p>
        </div>
        <!-- Feature Item 2 -->
        <div class="bg-gray-800 p-6 rounded-lg" data-aos="fade-up">
          <img loading="lazy" src="https://storage.googleapis.com/a1aa/image/8lKLw9vC9GLX3I1rK_VduFtFkijPc2G9DkLEWQMjRPg.jpg" alt="Custom car" class="mb-4 rounded" width="400" height="300">
          <h3 class="text-2xl font-bold mb-2">Customizable Cars</h3>
          <p>Customize your car with a variety of parts and paint jobs to make it your own.</p>
        </div>
        <!-- Feature Item 3 -->
        <div class="bg-gray-800 p-6 rounded-lg" data-aos="fade-left">
          <img loading="lazy" src="https://storage.googleapis.com/a1aa/image/FNixrvRJiTTYfsR7s3gVD3Qfh5ZjR0uk_q4iypsWa58.jpg" alt="Multiplayer racing" class="mb-4 rounded" width="400" height="300">
          <h3 class="text-2xl font-bold mb-2">Multiplayer Mode</h3>
          <p>Race against players from around the world in real-time multiplayer mode.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Download Section -->
  <section class="bg-gray-700 py-20">
    <div class="container mx-auto px-4 text-center" data-aos="zoom-in-up">
      <h2 class="text-4xl font-bold mb-8">Download Now</h2>
      <div class="flex justify-center space-x-4">
        <a href="#"><img loading="lazy" class="h-12" src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" alt="Google Play Store"></a>
        <a href="#"><img loading="lazy" class="h-12" src="https://upload.wikimedia.org/wikipedia/commons/6/67/Download_on_the_App_Store_Badge.svg" alt="Apple App Store"></a>
      </div>
    </div>
  </section>

 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Racing Game</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/alpinejs" defer></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet" />
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  <style>
    html { scroll-behavior: smooth; }
    body { font-family: 'Roboto', sans-serif; }
  </style>
</head>
<body class="bg-gray-900 text-white">

  <!-- Navigation Bar -->
  <nav class="bg-gray-800 p-4" x-data="{ open: false }">
    <div class="container mx-auto px-4 flex justify-between items-center">
      <a href="#" class="text-2xl font-bold">RacingGame</a>
      <div class="hidden md:flex space-x-4">
        <a href="#home" class="hover:text-gray-400">Home</a>
        <a href="#features" class="hover:text-gray-400">Features</a>
        <a href="#about" class="hover:text-gray-400">About</a>
        <a href="#contact" class="hover:text-gray-400">Contact</a>
      </div>
      <div class="md:hidden">
        <button @click="open = !open">
          <i class="fas fa-bars text-white text-xl"></i>
        </button>
      </div>
    </div>
    <div x-show="open" class="md:hidden px-4 pt-2 pb-4 space-y-2">
      <a href="#home" class="block hover:text-gray-400">Home</a>
      <a href="#features" class="block hover:text-gray-400">Features</a>
      <a href="#about" class="block hover:text-gray-400">About</a>
      <a href="#contact" class="block hover:text-gray-400">Contact</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="bg-gray-700 py-20">
    <div class="container mx-auto px-4 text-center" data-aos="zoom-in">
      <h1 class="text-5xl font-bold mb-4">Welcome to RacingGame</h1>
      <p class="text-xl mb-8">Experience the thrill of high-speed racing!</p>
      <a href="#" class="bg-blue-500 text-white px-6 py-3 rounded-full hover:bg-blue-600">Get Started</a>
    </div>
  </section>

  <!-- Features -->
  <section id="features" class="py-20">
    <div class="container mx-auto px-4">
      <h2 class="text-4xl font-bold text-center mb-12" data-aos="fade-up">Game Features</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Feature Item 1 -->
        <div class="bg-gray-800 p-6 rounded-lg" data-aos="fade-right">
          <img loading="lazy" src="https://storage.googleapis.com/a1aa/image/HIE5HJabm5EUae4hOau-Y7yA-scZeLwyHzHzqaO713o.jpg" alt="High-speed car" class="mb-4 rounded" width="400" height="300">
          <h3 class="text-2xl font-bold mb-2">High-Speed Racing</h3>
          <p>Experience the thrill of high-speed racing with realistic graphics and physics.</p>
        </div>
        <!-- Feature Item 2 -->
        <div class="bg-gray-800 p-6 rounded-lg" data-aos="fade-up">
          <img loading="lazy" src="https://storage.googleapis.com/a1aa/image/8lKLw9vC9GLX3I1rK_VduFtFkijPc2G9DkLEWQMjRPg.jpg" alt="Custom car" class="mb-4 rounded" width="400" height="300">
          <h3 class="text-2xl font-bold mb-2">Customizable Cars</h3>
          <p>Customize your car with a variety of parts and paint jobs to make it your own.</p>
        </div>
        <!-- Feature Item 3 -->
        <div class="bg-gray-800 p-6 rounded-lg" data-aos="fade-left">
          <img loading="lazy" src="https://storage.googleapis.com/a1aa/image/FNixrvRJiTTYfsR7s3gVD3Qfh5ZjR0uk_q4iypsWa58.jpg" alt="Multiplayer racing" class="mb-4 rounded" width="400" height="300">
          <h3 class="text-2xl font-bold mb-2">Multiplayer Mode</h3>
          <p>Race against players from around the world in real-time multiplayer mode.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Download Section -->
  <section class="bg-gray-700 py-20">
    <div class="container mx-auto px-4 text-center" data-aos="zoom-in-up">
      <h2 class="text-4xl font-bold mb-8">Download Now</h2>
      <div class="flex justify-center space-x-4">
        <a href="#"><img loading="lazy" class="h-12" src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" alt="Google Play Store"></a>
        <a href="#"><img loading="lazy" class="h-12" src="https://upload.wikimedia.org/wikipedia/commons/6/67/Download_on_the_App_Store_Badge.svg" alt="Apple App Store"></a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 py-6">
    <div class="container mx-auto px-4 text-center">
      <p>© 2025 RacingGame. All rights reserved.</p>
      <div class="flex justify-center space-x-4 mt-4">
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </footer>

  <!-- AOS Init -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Racing Game</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/alpinejs" defer></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet" />
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
  <style>
    html { scroll-behavior: smooth; }
    body { font-family: 'Roboto', sans-serif; }
  </style>
</head>
<body class="bg-gray-900 text-white">

  <!-- Navigation Bar -->
  <nav class="bg-gray-800 p-4" x-data="{ open: false }">
    <div class="container mx-auto px-4 flex justify-between items-center">
      <a href="#" class="text-2xl font-bold">RacingGame</a>
      <div class="hidden md:flex space-x-4">
        <a href="#home" class="hover:text-gray-400">Home</a>
        <a href="#features" class="hover:text-gray-400">Features</a>
        <a href="#about" class="hover:text-gray-400">About</a>
        <a href="#contact" class="hover:text-gray-400">Contact</a>
      </div>
      <div class="md:hidden">
        <button @click="open = !open">
          <i class="fas fa-bars text-white text-xl"></i>
        </button>
      </div>
    </div>
    <div x-show="open" class="md:hidden px-4 pt-2 pb-4 space-y-2">
      <a href="#home" class="block hover:text-gray-400">Home</a>
      <a href="#features" class="block hover:text-gray-400">Features</a>
      <a href="#about" class="block hover:text-gray-400">About</a>
      <a href="#contact" class="block hover:text-gray-400">Contact</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="bg-gray-700 py-20">
    <div class="container mx-auto px-4 text-center" data-aos="zoom-in">
      <h1 class="text-5xl font-bold mb-4">Welcome to RacingGame</h1>
      <p class="text-xl mb-8">Experience the thrill of high-speed racing!</p>
      <a href="#" class="bg-blue-500 text-white px-6 py-3 rounded-full hover:bg-blue-600">Get Started</a>
    </div>
  </section>

  <!-- Features -->
  <section id="features" class="py-20">
    <div class="container mx-auto px-4">
      <h2 class="text-4xl font-bold text-center mb-12" data-aos="fade-up">Game Features</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Feature Item 1 -->
        <div class="bg-gray-800 p-6 rounded-lg" data-aos="fade-right">
          <img loading="lazy" src="https://storage.googleapis.com/a1aa/image/HIE5HJabm5EUae4hOau-Y7yA-scZeLwyHzHzqaO713o.jpg" alt="High-speed car" class="mb-4 rounded" width="400" height="300">
          <h3 class="text-2xl font-bold mb-2">High-Speed Racing</h3>
          <p>Experience the thrill of high-speed racing with realistic graphics and physics.</p>
        </div>
        <!-- Feature Item 2 -->
        <div class="bg-gray-800 p-6 rounded-lg" data-aos="fade-up">
          <img loading="lazy" src="https://storage.googleapis.com/a1aa/image/8lKLw9vC9GLX3I1rK_VduFtFkijPc2G9DkLEWQMjRPg.jpg" alt="Custom car" class="mb-4 rounded" width="400" height="300">
          <h3 class="text-2xl font-bold mb-2">Customizable Cars</h3>
          <p>Customize your car with a variety of parts and paint jobs to make it your own.</p>
        </div>
        <!-- Feature Item 3 -->
        <div class="bg-gray-800 p-6 rounded-lg" data-aos="fade-left">
          <img loading="lazy" src="https://storage.googleapis.com/a1aa/image/FNixrvRJiTTYfsR7s3gVD3Qfh5ZjR0uk_q4iypsWa58.jpg" alt="Multiplayer racing" class="mb-4 rounded" width="400" height="300">
          <h3 class="text-2xl font-bold mb-2">Multiplayer Mode</h3>
          <p>Race against players from around the world in real-time multiplayer mode.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Download Section -->
  <section class="bg-gray-700 py-20">
    <div class="container mx-auto px-4 text-center" data-aos="zoom-in-up">
      <h2 class="text-4xl font-bold mb-8">Download Now</h2>
      <div class="flex justify-center space-x-4">
        <a href="#"><img loading="lazy" class="h-12" src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" alt="Google Play Store"></a>
        <a href="#"><img loading="lazy" class="h-12" src="https://upload.wikimedia.org/wikipedia/commons/6/67/Download_on_the_App_Store_Badge.svg" alt="Apple App Store"></a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 py-6">
    <div class="container mx-auto px-4 text-center">
      <p>© 2025 RacingGame. All rights reserved.</p>
      <div class="flex justify-center space-x-4 mt-4">
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </footer>

  <!-- AOS Init -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html>
