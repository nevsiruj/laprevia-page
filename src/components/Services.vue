<template>
  <section id="store" class="my-16">
    <h2 class="text-2xl font-bold text-center mb-8 text-blue-500">🛍️ Tienda</h2>
    <div class="container mx-auto">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="p-4">
          <div class="bg-white rounded-lg shadow-lg">
            <img
              src="https://via.placeholder.com/300x300"
              alt="Product 1"
              class="w-full h-48 object-cover rounded-lg mx-auto mb-4"
            />
            <h3 class="text-lg font-bold mt-4 text-center text-blue-500">
              Producto 1
            </h3>
            <a
              href="https://wa.me/5550123456789"
              class="
                mt-4
                block
                bg-green-500
                text-white
                font-bold
                py-2
                px-4
                rounded-full
                shadow-md
              "
            >
              <i class="fab fa-whatsapp mr-2"></i> Contactar
            </a>
          </div>
        </div>

        <div class="p-4">
          <div class="bg-white rounded-lg shadow-lg">
            <img
              src="https://via.placeholder.com/300x300"
              alt="Product 2"
              class="w-full h-48 object-cover rounded-lg mx-auto mb-4"
            />
            <h3 class="text-lg font-bold mt-4 text-center text-blue-500">
              Producto 2
            </h3>
            <a
              href="https://wa.me/5550123456789"
              class="
                mt-4
                block
                bg-green-500
                text-white
                font-bold
                py-2
                px-4
                rounded-full
                shadow-md
              "
            >
              <i class="fab fa-whatsapp mr-2"></i> Contactar
            </a>
          </div>
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
