<template>
  <section id="contact" class="my-16">
    <div class="container mx-auto">
      <div class="p-8 bg-white rounded-lg shadow-lg">
        <h2 class="text-2xl font-bold text-center mb-8 text-blue-500">
          📞 Contacto
        </h2>
        <div class="text-center">
          <p class="text-lg mb-4">
            ¿Tienes alguna duda o quieres hacer un pedido? 💬 Escríbenos por
            Whatsapp o llámanos al 3544444428.
          </p>
          <div class="flex justify-around">
            <a
              href="https://wa.me/3544444428"
              class="
                bg-green-500
                text-white
                font-bold
                py-2
                px-4
                rounded-full
                shadow-md
              "
            >
              <i class="fab fa-whatsapp mr-2"></i> Escríbenos
            </a>
            <a
              href="tel:3544444428"
              class="
                bg-green-500
                text-white
                font-bold
                py-2
                px-4
                rounded-full
                shadow-md
              "
            >
              <i class="fas fa-phone mr-2"></i> Llamar
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="locations" class="my-16">
    <h2 class="text-2xl font-bold text-center mb-8 text-blue-500">
      📍 Ubicaciones
    </h2>
    <div class="container mx-auto">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="bg-white p-8 rounded-lg shadow-lg">
          <p class="text-lg font-bold text-blue-500">25 de Mayo 189</p>
          <p class="text-gray-600">Villa Dolores</p>
        </div>
        <div class="bg-white p-8 rounded-lg shadow-lg">
          <p class="text-lg font-bold text-blue-500">Belgrano 1088</p>
          <p class="text-gray-600">Villa Dolores</p>
        </div>
        <div class="bg-white p-8 rounded-lg shadow-lg">
          <p class="text-lg font-bold text-blue-500">Av Cuestas 37</p>
          <p class="text-gray-600">Villa Sarmiento</p>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.shadow-lg {
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1),
    0 4px 6px -2px rgba(0, 0, 0, 0.05);
}
</style>

<script>
export default {
  name: 'ContactSection',
};
</script>
