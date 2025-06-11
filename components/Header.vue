<script setup>
import { ref } from "vue";
const isMenuOpen = ref(true);
const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value;
};
</script>
<template>
  <!-- Header -->
  <header class="flex justify-between md:px-[12rem] py-7">
    <!-- Logo -->
    <div>
      <img src="../public/images/logo.svg" alt="Logo" />
    </div>

    <!-- Icon hamburger -->
    <div @click="toggleMenu" class="md:hidden">
      <img src="../public/images/icon-hamburger.svg" alt="" />
    </div>

    <!-- Navigation -->
    <nav
      v-if="isMenuOpen"
      :class="['hidden md:block', isMenuOpen ? 'block' : 'hidden']"
    >
      <ul class="flex flex-col md:flex-row space-x-7">
        <li><a href="">How we work</a></li>
        <li><a href="">Blog</a></li>
        <li><a href="">Account</a></li>
        <li>
          <a
            class="border-2 border-blue-950 border-solid hover:bg-blue-950 hover:text-white py-2 px-7"
            href=""
            >View plans</a
          >
        </li>
      </ul>
    </nav>
  </header>
</template>
