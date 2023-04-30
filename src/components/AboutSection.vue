<template>
  <section class="bg-gray-900 py-16">
    <div
      class="
        container
        mx-auto
        flex flex-col
        md:flex-row
        items-center
        justify-between
      "
    >
      <div class="md:w-1/2 mb-8">
        <!-- <img src="./assets/gonzalo.jpg" alt="Gonzalo Suarez" class="w-full h-auto rounded-lg shadow-lg"> -->
      </div>
      <div class="md:w-1/2 text-center md:text-left">
        <h2 class="text-3xl font-bold text-white mb-8">
          Acerca de Gonzalo Suarez
        </h2>
        <p class="text-gray-300 text-xl mb-8">
          Soy Gonzalo Suarez, un Fullstack Developer con experiencia en el
          desarrollo de aplicaciones web y móviles. Me apasiona crear soluciones
          innovadoras y eficientes para los problemas de mis clientes.
        </p>
        <p class="text-gray-300 text-xl mb-8">
          Mi experiencia abarca desde el desarrollo de aplicaciones front-end
          utilizando tecnologías como Vue.js, React y Angular, hasta la creación
          de APIs y sistemas back-end utilizando Node.js y MongoDB.
        </p>
        <p class="text-gray-300 text-xl mb-8">
          Si estás buscando un desarrollador experimentado que pueda ayudarte a
          llevar tus ideas al siguiente nivel, ¡no dudes en contactarme!
        </p>
        <a
          href="#"
          class="
            bg-green-700
            hover:bg-green-900
            text-white
            font-bold
            py-2
            px-4
            rounded
            inline-block
          "
          >Contactar</a
        >
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'AboutSection',
  components: {},
  props: {},
  data() {
    return {};
  },
  computed: {},
  methods: {},
};
</script>
<style scoped>
/* Estilos para la sección Acerca de */
</style>
