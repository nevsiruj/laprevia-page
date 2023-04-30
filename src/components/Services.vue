<template>
  <section id="best-sellers" class="my-16">
    <h2 class="text-2xl font-bold text-center mb-8 text-gray-900">
      🔥 Más vendidos
    </h2>
    <div class="container mx-auto">
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
        <div class="bg-white p-8 rounded-lg shadow-lg">
          <img
            src="https://via.placeholder.com/300x300"
            alt="Product 1"
            class="w-full h-64 object-cover rounded-lg"
          />
          <h3 class="text-lg font-bold mt-4 text-blue-500">Producto 1</h3>
        </div>
        <div class="bg-white p-8 rounded-lg shadow-lg">
          <img
            src="https://via.placeholder.com/300x300"
            alt="Product 2"
            class="w-full h-64 object-cover rounded-lg"
          />
          <h3 class="text-lg font-bold mt-4 text-blue-500">Producto 2</h3>
        </div>
        <div class="bg-white p-8 rounded-lg shadow-lg">
          <img
            src="https://via.placeholder.com/300x300"
            alt="Product 3"
            class="w-full h-64 object-cover rounded-lg"
          />
          <h3 class="text-lg font-bold mt-4 text-blue-500">Producto 3</h3>
        </div>
        <div class="bg-white p-8 rounded-lg shadow-lg">
          <img
            src="https://via.placeholder.com/300x300"
            alt="Product 4"
            class="w-full h-64 object-cover rounded-lg"
          />
          <h3 class="text-lg font-bold mt-4 text-blue-500">Producto 4</h3>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'PopularProducts',
};
</script>
<style>
.shadow-lg {
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1),
    0 4px 6px -2px rgba(0, 0, 0, 0.05);
}
</style>
