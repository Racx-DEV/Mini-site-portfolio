<template>
  <section class="min-h-screen flex flex-col items-center justify-center bg-[#f6f8fb] px-4">
    <div class="w-full max-w-md bg-white p-8 rounded-2xl shadow-2xl border border-neutral-300">
      <h1 class="text-2xl font-semibold mb-4 text-[#071427] text-center">Contato</h1>
      <form class="space-y-4">
        <div>
          <label class="block mb-1 text-neutral-600">Nome</label>
          <input type="text" placeholder="Seu nome" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-400"/>
        </div>
        <div>
          <label class="block mb-1 text-neutral-600">E-mail</label>
          <input type="email" placeholder="seu@email.com" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-400"/>
        </div>
        <div>
          <label class="block mb-1 text-neutral-600">Mensagem</label>
          <textarea placeholder="Digite sua mensagem" rows="4" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-400"></textarea>
        </div>
        <button type="button" class="w-full bg-[#071427] text-white py-2 rounded-lg hover:bg-blue-600 transition">Enviar</button>
      </form>
      <!-- Redes Sociais -->
      <div class="flex justify-center space-x-6 mt-8">
        <!-- Instagram -->
        <a href="https://www.instagram.com/raulfv_14/" target="_blank" title="Instagram">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48" class="w-8 h-8">
            <radialGradient id="yOrnnhliCrdS2gy~4tD8ma_Xy10Jcu1L2Su_gr1" cx="19.38" cy="42.035" r="44.899" gradientUnits="userSpaceOnUse">
              <stop offset="0" stop-color="#fd5"></stop>
              <stop offset=".328" stop-color="#ff543f"></stop>
              <stop offset=".348" stop-color="#fc5245"></stop>
              <stop offset=".504" stop-color="#e64771"></stop>
              <stop offset=".643" stop-color="#d53e91"></stop>
              <stop offset=".761" stop-color="#cc39a4"></stop>
              <stop offset=".841" stop-color="#c837ab"></stop>
            </radialGradient>
            <path fill="url(#yOrnnhliCrdS2gy~4tD8ma_Xy10Jcu1L2Su_gr1)" d="M34.017,41.99l-20,0.019c-4.4,0.004-8.003-3.592-8.008-7.992l-0.019-20	c-0.004-4.4,3.592-8.003,7.992-8.008l20-0.019c4.4-0.004,8.003,3.592,8.008,7.992l0.019,20	C42.014,38.383,38.417,41.986,34.017,41.99z"></path>
            <radialGradient id="yOrnnhliCrdS2gy~4tD8mb_Xy10Jcu1L2Su_gr2" cx="11.786" cy="5.54" r="29.813" gradientTransform="matrix(1 0 0 .6663 0 1.849)" gradientUnits="userSpaceOnUse">
              <stop offset="0" stop-color="#4168c9"></stop>
              <stop offset=".999" stop-color="#4168c9" stop-opacity="0"></stop>
            </radialGradient>
            <path fill="url(#yOrnnhliCrdS2gy~4tD8mb_Xy10Jcu1L2Su_gr2)" d="M34.017,41.99l-20,0.019c-4.4,0.004-8.003-3.592-8.008-7.992l-0.019-20	c-0.004-4.4,3.592-8.003,7.992-8.008l20-0.019c4.4-0.004,8.003,3.592,8.008,7.992l0.019,20	C42.014,38.383,38.417,41.986,34.017,41.99z"></path>
            <path fill="#fff" d="M24,31c-3.859,0-7-3.14-7-7s3.141-7,7-7s7,3.14,7,7S27.859,31,24,31z M24,19c-2.757,0-5,2.243-5,5	s2.243,5,5,5s5-2.243,5-5S26.757,19,24,19z"></path>
            <circle cx="31.5" cy="16.5" r="1.5" fill="#fff"></circle>
            <path fill="#fff" d="M30,37H18c-3.859,0-7-3.14-7-7V18c0-3.86,3.141-7,7-7h12c3.859,0,7,3.14,7,7v12	C37,33.86,33.859,37,30,37z M18,13c-2.757,0-5,2.243-5,5v12c0,2.757,2.243,5,5,5h12c2.757,0,5-2.243,5-5V18c0-2.757-2.243-5-5-5H18z"></path>
          </svg>
        </a>
        <!-- LinkedIn -->
        <a href="https://www.linkedin.com/in/raul-fabiano" target="_blank" title="LinkedIn">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48" class="w-8 h-8">
            <path fill="#0288D1" d="M42,37c0,2.762-2.238,5-5,5H11c-2.761,0-5-2.238-5-5V11c0-2.762,2.239-5,5-5h26c2.762,0,5,2.238,5,5V37z"></path>
            <path fill="#FFF" d="M12 19H17V36H12zM14.485 17h-.028C12.965 17 12 15.888 12 14.499 12 13.08 12.995 12 14.514 12c1.521 0 2.458 1.08 2.486 2.499C17 15.887 16.035 17 14.485 17zM36 36h-5v-9.099c0-2.198-1.225-3.698-3.192-3.698-1.501 0-2.313 1.012-2.707 1.99C24.957 25.543 25 26.511 25 27v9h-5V19h5v2.616C25.721 20.5 26.85 19 29.738 19c3.578 0 6.261 2.25 6.261 7.274L36 36 36 36z"></path>
          </svg>
        </a>
        <!-- E-mail -->
        <a href="mailto:raulfabiano.dev@gmail.com" title="E-mail">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75" />
          </svg>
        </a>
      </div>
    </div>
  </section>
</template>
