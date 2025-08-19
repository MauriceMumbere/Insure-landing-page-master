<script setup>
import { ref } from "vue";

const isMenuOpen = ref(false);

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value;
};
</script>

<template>
  <!-- Header -->
  <header class="flex justify-between md:px-[12rem] px-5 py-7 items-center">
    <!-- Logo -->
    <div>
      <img src="/images/logo.svg" alt="Logo" />
    </div>

    <!-- Icon hamburger -->
    <div @click="toggleMenu" class="md:hidden cursor-pointer">
      <img
        :src="
          isMenuOpen ? '/images/icon-close.svg' : '/images/icon-hamburger.svg'
        "
        :alt="isMenuOpen ? 'Close menu' : 'Open menu'"
      />
    </div>

    <!-- Navigation -->
    <!-- Navigation -->
    <nav
      :class="[
        // Mobile
        isMenuOpen ? 'block' : 'hidden',
        'absolute z-50 h-[90%] bg-blue-950 top-20 right-0 left-0 text-white',
        // Desktop
        'md:static md:block md:h-auto md:bg-white md:text-black',
      ]"
    >
      <div
        class="absolute bottom-0 inset-0 bg-[url('/images/bg-pattern-mobile-nav.svg')] md:bg-none bg-no-repeat bg-bottom md:z-10 pointer-events-none"
      ></div>

      <ul
        class="flex flex-col items-center text-center md:text-left md:flex-row md:space-x-7 space-y-10 md:space-y-0 p-5 md:p-0"
      >
        <li>
          <a
            class="font-bold text-2xl opacity-40 hover:text-blue-950 hover:opacity-100 md:text-[1rem]"
            href="#"
          >
            How we work
          </a>
        </li>
        <li>
          <a
            class="font-bold text-2xl opacity-40 hover:text-blue-950 hover:opacity-100 md:text-[1rem]"
            href="#"
          >
            Blog
          </a>
        </li>
        <li>
          <a
            class="font-bold text-2xl opacity-40 hover:text-blue-950 hover:opacity-100 md:text-[1rem]"
            href="#"
          >
            Account
          </a>
        </li>
        <li>
          <a
            class="border-2 border-white md:border-blue-950 border-solid hover:bg-blue-950 hover:text-white py-2 px-7 w-full font-bold text-2xl md:font-normal md:text-[1rem]"
            href="#"
          >
            View plans
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>
