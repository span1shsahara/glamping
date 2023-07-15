<template>
  <div>
    <!-- Navbar -->
    <nav class="bg-white py-4">
      <div class="container mx-auto flex justify-between items-center px-4">
        <!-- Logo -->
        <div class="mr-2">
      <img class="h-60 w-[50%]" src="/IMG/LogoMonteCieloGlamping-02.svg" alt="Logo" >
    </div>
        <!-- Navigation links -->
        <ul class="flex space-x-4">
          <li><a class="text-black font-medium font-montserrat" href="#">Home</a></li>
          <li><a class="text-black font-medium font-montserrat" href="#">Blog</a></li>
          <li><a class="text-black font-medium font-montserrat" href="#">Rooms</a></li>
          <li><a class="text-black font-medium font-montserrat" href="#">Contact</a></li>
        </ul>
      </div>
    </nav>

    <main class="container mx-auto py-8">
      <!-- Hostel images -->
      <img src="\IMG\BANNER-PRINCIPAL.jpg" alt="Hostel Image" class="w-full h-auto mb-4">

      <!-- Page content goes here -->
      <h1 class="text-3xl font-bold mb-4">Welcome to My Website</h1>
      <p class="font-medium font-montserrat text-lg">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed at eros tincidunt, consectetur libero eu, faucibus sapien. Quisque ullamcorper sapien et venenatis pellentesque.</p>
    </main>

    
    <footer class="bg-gray-200 py-4">
      <div class="container mx-auto px-4">
        <!-- Footer content -->
        <p class="text-center text-gray-600 font-medium font-montserrat">© 2023 My Website. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');

.font-montserrat {
  font-family: 'Montserrat', sans-serif;
}
</style>
