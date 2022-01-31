<template>
  <section class="px-36 py-12 relative">
    <a
      href="#services"
      class="
        uppercase
        tracking-widest
        absolute
        right-0
        rotate-90
        top-20
        font-bold
      "
      >Services</a
    >
    <!-- Card -->
    <div
      class="
        bg-orange-100 bg-opacity-40
        p-24
        relative
        overflow-hidden
        rounded-2xl
      "
    >
      <img
        :src="Phone"
        class="
          absolute
          w-[45rem]
          -rotate-45
          right-2
          top-10
          z-0
          bg-cover bg-no-repeat
        "
        alt=""
      />
      <div
        class="
          bg-orange-200
          relative
          z-10
          w-16
          h-16
          py-4
          flex
          justify-center
          items-center
          rounded-full
          mb-8
        "
      >
        <i class="uil uil-layer-group text-3xl"></i>
      </div>

      <h2 class="font-bold text-4xl mb-4 z-10 relative">Branding</h2>
      <p class="max-w-[28rem] mb-8 opacity-70 leading-7 z-10">
        I build and create automation and information systems for clients and
        organizations. Mostly thesis/capstone projects.
      </p>

      <a href="#projects" class="uppercase font-semibold z-10 relative"
        >See Projects</a
      >
    </div>
  </section>
</template>

<script>
import Phone from "../assets/phone.png";
export default {
  data() {
    return {
      Phone,
    };
  },
};
</script>

<style>
</style>