<template>
  <section class="bg-gray-100 py-16">
    <div class="container mx-auto flex flex-col items-center justify-center">
      <h2 class="text-3xl font-bold text-black-900 text-center mb-8">
        Testimonios
      </h2>
      <div class="max-w-lg mx-auto mb-8">
        <p class="text-black-900 text-center text-xl">
          Estos son algunos testimonios de mis clientes satisfechos
        </p>
      </div>
      <div class="flex flex-wrap justify-center">
        <div class="w-full md:w-1/2 lg:w-1/3 p-4">
          <div
            class="
              bg-gray-800
              rounded-lg
              shadow-lg
              p-6
              text-center
              animate__animated animate__fadeInLeft
            "
          >
            <p class="text-gray-200 text-lg mb-4">
              "Gonzalo es un excelente profesional. Su trabajo es de alta
              calidad, siempre cumple con los plazos y es muy comunicativo. ¡Lo
              recomiendo altamente!"
            </p>
            <p class="text-green-500 font-bold">María Rodríguez</p>
            <p class="text-green-500">CEO de ABC Company</p>
          </div>
        </div>
        <div class="w-full md:w-1/2 lg:w-1/3 p-4">
          <div
            class="
              bg-gray-800
              rounded-lg
              shadow-lg
              p-6
              text-center
              animate__animated animate__fadeInRight
            "
          >
            <p class="text-gray-200 text-lg mb-4">
              "Gonzalo es una persona muy comprometida con su trabajo y siempre
              busca la mejor solución para sus clientes. Siempre es un placer
              trabajar con él."
            </p>
            <p class="text-green-500 font-bold">Pedro Gómez</p>
            <p class="text-green-500">Gerente de marketing de XYZ Company</p>
          </div>
        </div>
        <div class="w-full md:w-1/2 lg:w-1/3 p-4">
          <div
            class="
              bg-gray-800
              rounded-lg
              shadow-lg
              p-6
              text-center
              animate__animated animate__fadeInLeft
            "
          >
            <p class="text-gray-200 text-lg mb-4">
              "Trabajar con Gonzalo ha sido una experiencia muy positiva. Es un
              excelente desarrollador y siempre se asegura de que sus clientes
              estén satisfechos con su trabajo."
            </p>
            <p class="text-green-500 font-bold">Roberto Pérez</p>
            <p class="text-green-500">CEO de 123 Company</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style scoped>
@import '~animate.css';
.bg-gray-800 {
  background-color: #2d3748;
}

.text-gray-200 {
  color: #e2e8f0;
}
</style>
