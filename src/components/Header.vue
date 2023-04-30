<template>
  <header class="bg-blue-500 text-white w-full py-4 px-8">
    <div class="container mx-auto flex justify-between items-center">
      <h1
        class="
          text-2xl
          font-bold
          text-white
          cursor-pointer
          hover:text-white
          transition-colors
          duration-300
        "
      >
        La Previa
      </h1>
      <nav class="text-white">
        <ul class="flex">
          <li class="mx-4">
            <a href="#products" class="hover:text-white">Productos</a>
          </li>
          <li class="mx-4">
            <a href="#about" class="hover:text-white">Acerca de</a>
          </li>
          <li class="mx-4">
            <a href="#contact" class="hover:text-white">Contacto</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style>
header {
  transition: background-color 0.5s ease;
}

header:hover {
  background-color: #2c5282;
}

.bg-blue-800 {
  background-color: #2b6cb0;
}
</style>
