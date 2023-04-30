<template>
  <footer class="bg-blue-100 text-gray-800 py-4">
    <div
      class="
        container
        mx-auto
        flex flex-col
        md:flex-row
        justify-between
        items-center
      "
    >
      <div class="text-center mb-4 md:mb-0">
        <h4 class="text-2xl font-semibold text-blue-500">La Previa</h4>
        <p class="text-gray-500">
          <a
            href="https://wa.me/+543544444428"
            target="_blank"
            rel="noopener noreferrer"
            class="
              inline-flex
              items-center
              px-4
              py-2
              text-gray-900
              bg-green-200
              rounded
              hover:bg-green-300
            "
          >
            <i class="fab fa-whatsapp mr-1"></i>
            Chat WhatsApp
          </a>
        </p>
      </div>

      <div class="flex justify-center items-center space-x-4">
        <a
          href="https://www.instagram.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="text-blue-400 hover:text-blue-700"
        >
          <i class="fab fa-instagram fa-lg"></i>
        </a>
        <a
          href="https://www.facebook.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="text-blue-400 hover:text-blue-700"
        >
          <i class="fab fa-facebook fa-lg"></i>
        </a>
      </div>
    </div>
  </footer>
</template>
<script>
export default {};
</script>
<style scoped>
/* @import 'https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.16/tailwind.min.css'; */
footer {
  background-color: #f1f8ff;
}
footer h4 {
  color: #007bff;
}

footer a:hover {
  color: #007bff;
}
</style>
