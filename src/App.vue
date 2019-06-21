<template>
  <div id="app" class="font-body antialiased text-lg">
    <nav class="bg-purple-400 shadow-md">
      <div class="container mx-auto p-4 flex flex-col sm:flex-row justify-between items-center">
        <h1 class="font-display text-4xl text-center sm:text-left">Inner Lanscapes</h1>
        <h1 class="font-display text-2xl text-center sm:text-left">Henrieta Pribulova</h1>
      </div>
    </nav>
    <router-view/>
    <footer class="bg-gray-800 text-white text-center shadow-md">
      <div class="container mx-auto p-4">
        <h3>Have a lovely day 🌼</h3>
      </div>
    </footer>
  </div>
</template>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css?family=Amatic+SC|Buda:300|Raleway:400,600&display=swap');

@tailwind base;

p {
  margin-bottom: 15px;
}

@tailwind components;

@tailwind utilities;
</style>
