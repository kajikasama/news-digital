<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import Navbar from '../Components/Navbar.vue';

</script>

<template>

  <Head title="Homepage" />
  <div>
    <Navbar />
    <section class="judul max-w-6xl mx-auto py-10">
      <p class="text-5xl text-grey-700 ">News Chanbaram</p>
    </section>

    <section class="card max-w-6xl mx-auto flex items-center justify-between shadow-lg">
      <div class="w-1/4 items-center"><img class="" src="img/badut.png" alt=""></div>
      <div class="w-3/4 px-8 pt-4 pb-5 space-y-5">
        <p class="text-grey-900 text-2xl">30 Juli 2022</p>
        <h4 class="text-grey-800 text-4xl font-bold">Negara Wakanda Blokir Karena Baper</h4>
        <p class="text-grey-200">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Animi ipsam quidem sapiente natus veniam autem aperiam reiciendis minima quasi molestias perspiciatis distinctio quibusdam maiores incidunt, voluptatum error, in mollitia libero voluptate. Aliquid perferendis facere est sapiente illum nostrum alias facilis non sint dignissimos molestias quaerat veritatis iure quam, fugit ...
        </p>
        <div class="flex justify-end">
          <button class="p-4 bg-sky-400 text-white transition duration-300 hover:bg-sky-500">Baca Selengkapnya</button>
        </div>
      </div>
    </section>
  </div>

</template>

<style scoped>
</style>
