<!DOCTYPE html>
<html lang="id">
 <head>
  <meta charset="utf-8"/>
  <meta http-equiv="refresh" content="5">
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  </body>
  <div class="container">
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Roboto', sans-serif;
    }
  </style>
 </head>
 <body class="bg-gray-100 min-h-screen flex flex-col">
  <header class="bg-white shadow-md">
   <div class="container mx-auto px-4 py-4 flex items-center justify-between">
    <div class="flex items-center space-x-3">
     <img alt="Ikon wajah karakter anime bergaya dengan mata besar dan rambut berwarna-warni" class="w-12 h-12 rounded-full" height="48" src="https://storage.googleapis.com/a1aa/image/13211957-d4bb-4883-de04-93292664b9e4.jpg" width="48"/>
     <h1 class="text-2xl font-bold text-gray-900">
      TofikDev
     </h1>
    </div>
    <nav class="hidden md:flex space-x-6 text-gray-700 font-medium">
     <a class="hover:text-red-600 transition" href="#">
      Beranda
     </a>
     <a class="hover:text-red-600 transition" href="#">
      2D Android
     </a>
     <a class="hover:text-red-600 transition" href="#">
      Animasi
     </a>
     <a class="hover:text-red-600 transition" href="#">
      p
     </a>
     <a class="hover:text-red-600 transition" href="#">
      p
     </a>
    </nav>
    <button aria-label="Toggle menu" class="md:hidden text-gray-700 focus:outline-none focus:ring-2 focus:ring-red-600" id="menu-btn">
     <i class="fas fa-bars fa-lg">
     </i>
    </button>
   </div>
   <nav class="md:hidden bg-white border-t border-gray-200 hidden" id="mobile-menu">
    <a class="block px-4 py-3 text-gray-700 hover:bg-red-50 hover:text-red-600 font-medium" href="#">
     Beranda
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-red-50 hover:text-red-600 font-medium" href="#">
     2D Android
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-red-50 hover:text-red-600 font-medium" href="#">
     Animasi
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-red-50 hover:text-red-600 font-medium" href="#">
     web
    </a>
    <a class="block px-4 py-3 text-gray-700 hover:bg-red-50 hover:text-red-600 font-medium" href="#">
     php
    </a>
   </nav>
  </header>
  <main class="flex-grow container mx-auto px-4 py-8">
   <section class="max-w-4xl mx-auto bg-white rounded-lg shadow-md p-6">
    <div class="flex flex-col items-center space-y-6">
     <img alt="Karakter robot android bergaya anime 2D yang cerah dengan efek anberwarna-warni, mewakili mode pemeliharaan" class="w-full rounded-lg object-cover" height="400" src="https://storage.googleapis.com/a1aa/image/ae36ddf8-b372-49c1-4141-cc4db6dd3130.jpg" width="600"/>
     <h2 class="text-3xl font-extrabold text-gray-900 text-center">
      <h2><?= htmlspecialchars($data['message2']) ?></h2>
     </h2>
     <p class="text-gray-700 text-center max-w-xl">
      <p>🚧 Mode Pemeliharaan</p>
    <p><?= htmlspecialchars($data['message']) ?></p>
     </p>
     <button class="mt-4 px-6 py-3 bg-red-600 text-white font-semibold rounded-md cursor-not-allowed opacity-70" disabled="">
      Silakan cek kembali nanti
     </button>
    </div>
   </section>
  </main>
  <footer class="bg-white border-t border-gray-200 py-6 mt-12">
   <div class="container mx-auto px-4 text-center text-gray-600 text-sm">
    © 2025  Semua hak dilindungi.
   </div>
  </footer>
  <script>
   const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');

    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>
  </div>
</body>
</html>

