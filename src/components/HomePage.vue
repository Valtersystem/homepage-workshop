<script setup>
import Aboutworkshop from '../components/AboutWorkshop.vue';
import Price from '../components/Price.vue';
</script>

<template>
<!-- Section Header -->
<section class="overflow-hidden bg-gray-50 sm:grid sm:grid-cols-2 sm:items-center">
  <div class="p-8 md:p-12 lg:px-16 lg:py-24">
    <div class="mx-auto max-w-xl text-left ltr:sm:text-left rtl:sm:text-right">
      <h2 class="text-2xl font-bold text-gray-900 md:text-3xl uppercase">
        Construa uma família saudável conosco!
      </h2>

      <p class="text-gray-500 mt-4 md:mt-4 md:block">
        Olá, fulano (a)!
      </p>
      <p class="text-gray-500 md:mt-4 md:block">
        Eu sou o Marcus Solon. Ao longo de minha carreira como Engenheiro Civil e Terapeuta Familiar Sistêmico, tenho ajudado famílias a restaurarem seus laços e encontrarem equilíbrio emocional.

      </p>
      <p class="text-gray-500 md:mt-4 md:block">
        Convido você a participar do nosso Workshop Família Saudável. Nele, compartilharemos estratégias práticas para fortalecer os vínculos familiares e resolver conflitos de forma eficaz.
      </p>

      <p class="text-gray-500 md:mt-4 md:block">
        Reserve sua vaga agora mesmo e transforme sua vida familiar para melhor!
      </p>

      <p class="text-gray-500 md:mt-4 md:block">
        <strong>
          <i class="fa-solid fa-calendar-days"></i> Data: April 13, 2024  <br>
          <i class="fa-solid fa-clock"></i> Horário: 8:30 AM às 12:30 PM <br>
          <i class="fa-solid fa-location-dot"></i> Localização: Rua de Faria Guimarães, 798, Porto, Porto, Portugal
        </strong>
      </p>

      <div class="mt-4 md:mt-8">
        <a
          href="#price"
          class="inline-block rounded bg-yellow-300 px-12 py-3 text-sm font-medium text-white transition hover:bg-yellow-600 focus:outline-none focus:ring"
        >
        Investir
        </a>
      </div>
    </div>
  </div>

  <img
    alt=""
    src="../../public/family.jpg"
    class="h-full w-full object-cover sm:h-[calc(100%_-_2rem)] sm:self-end sm:rounded-ss-[30px] md:h-[calc(100%_-_4rem)] md:rounded-ss-[60px]"
  />
</section>
<!-- Section Header -->

<!--  -->
<Aboutworkshop />
<!--  -->
<!--  -->
<Price />
<!--  -->
</template>