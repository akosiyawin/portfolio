<template>
  <section class="pl-12 pr-60 py-12 relative">
    <!-- Card -->
    <div
      class="
        grid grid-cols-3
        bg-sky-50 bg-opacity-80
        p-24
        relative
        overflow-hidden
        rounded-2xl
      "
    >
      <div class="col-span-2">
        <div
          class="
            bg-red-300
            w-[14rem]
            h-[18rem]
            align-middle
            absolute
            overflow-hidden
            rounded-b
            shadow-lg
            -top-8
          "
        >
          <img
            :src="Achievement2"
            class="min-w-[25rem] -left-[5.5rem] absolute"
            alt=""
          />
        </div>

        <div
          class="
            bg-white
            w-[17.8rem]
            h-[23rem]
            align-middle
            absolute
            overflow-hidden
            rounded-t-xl
            shadow-lg
            left-[24rem]
            bottom-0
          "
        >
          <img
            :src="Achievement1"
            class="min-w-[20rem] -left-6 bottom-5 absolute"
            alt=""
          />
        </div>

        <div
          class="
            bg-red-300
            w-[14rem]
            h-[18.5rem]
            align-middle
            absolute
            overflow-hidden
            rounded-t
            shadow-lg
            -bottom-36
          "
        >
          <img
            :src="Achievement3"
            class="min-w-[25rem] -left-[7rem] absolute -top-10"
            alt=""
          />
        </div>
      </div>
      <div>
        <div
          class="
            bg-sky-200 bg-opacity-50
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
          <i class="uil uil-award text-3xl"></i>
        </div>

        <h2 class="font-bold text-4xl mb-4 z-10 relative">Achievements</h2>
        <p class="max-w-[28rem] mb-8 opacity-70 leading-7 z-10">
          I build and create automation and information systems for clients and
          organizations. Mostly thesis/capstone projects.
        </p>

        <a
          href="#projects"
          class="
            uppercase
            font-semibold
            z-10
            relative
            underline underline-offset-2
          "
          >See Achievements</a
        >
      </div>
    </div>
  </section>
</template>

<script>
import Achievement1 from "../assets/achievement1.jpg";
import Achievement2 from "../assets/achievement2.jpg";
import Achievement3 from "../assets/achievement3.jpg";
export default {
  data() {
    return {
      Achievement1,
      Achievement2,
      Achievement3,
    };
  },
};
</script>

<style>
</style>