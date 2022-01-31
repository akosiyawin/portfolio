<template>
  <section
    class="container grid grid-cols-2 pl-64 items-center pt-20 pb-8 relative"
  >
    <!-- Socials -->
    <div class="text-3xl grid grid-cols-1 gap-4 absolute left-12 bottom-10">
      <a href="#">
        <i class="uil uil-facebook-f"></i>
      </a>
      <a href="#">
        <i class="uil uil-instagram"></i>
      </a>
      <a href="#">
        <i class="uil uil-github"></i>
      </a>
    </div>
    <div>
      <div>
        <h1 class="text-7xl tracking-wider font-bold mb-10">
          Darwin <br />
          Marcelo
        </h1>
        <p class="uppercase tracking-wider max-w-[16rem] mb-10 text-xl">
          Backend Engineer and Critical Thinker
        </p>
      </div>

      <p class="text-base leading-7 mb-20 opacity-70">
        You are a frontend engineer and you love <br />
        making projects just like me! Let's shake hands, bro 🤝
      </p>

      <button
        class="px-8 py-4 uppercase rounded-xl font-semibold bg-stone-800 text-white"
      >
        Let's Chat!
      </button>
    </div>
    <div class="">
      <img :src="IOT" class="relative w-[40rem] -top-20" alt="iot image" />
    </div>
  </section>
</template>

<script>
import IOT from "../assets/IOT.svg";

export default {
  data() {
    return {
      IOT,
    };
  },
};
</script>
