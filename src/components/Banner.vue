<template>
  <div
    class="
      w-full
      max-w-sm
      mx-auto
      mt-16
      shadow-lg
      animate__animated animate__fadeInUp
    "
  >
    <div class="bg-blue-500 text-white p-8">
      <h1 class="text-4xl font-bold mb-4">Bienvenido a La Previa</h1>
      <p class="text-lg mb-8">
        Ofrecemos una amplia selección de bebidas para todos los gustos
      </p>
      <a
        href="#products"
        class="
          bg-white
          hover:bg-gray-200
          text-blue-800
          font-bold
          py-2
          px-4
          rounded-full
          animated
          pulse
        "
        >Explora nuestros productos</a
      >
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSection',
};
</script>

<style>
.bg-blue-600 {
  background-color: #3182ce;
}

.bg-white {
  background-color: #ffffff;
}

.hover:bg-gray-200 {
  background-color: #edf2f7;
}

.text-blue-800 {
  color: #2b6cb0;
}

.shadow-lg {
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1),
    0 4px 6px -2px rgba(0, 0, 0, 0.05);
}
</style>
