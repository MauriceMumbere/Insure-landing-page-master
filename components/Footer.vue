<template>
  <footer
    class="px-5 md:px-[12rem] py-20 bg-gray-50 bg-[url('./images/bg-pattern-footer-desktop.svg')] bg-no-repeat bg-top-left"
  >
    <div
      class="flex flex-col space-y-9 justify-center items-center md:flex-row md:justify-between border-b-2 border-black pb-10 text-center"
    >
      <div>
        <img src="../public/images/logo.svg" alt="Logo" />
      </div>
      <div>
        <ul class="flex items-center space-x-4">
          <li>
            <a
              href="#"
              class="flex items-center justify-center w-10 h-10 rounded-full transition-colors duration-300 hover:bg-blue-950"
            >
              <img src="/images/icon-facebook.svg" alt="Facebook icon" />
            </a>
          </li>
          <li>
            <a
              href="#"
              class="flex items-center justify-center w-10 h-10 rounded-full transition-colors duration-300 hover:bg-blue-950"
            >
              <img src="/images/icon-twitter.svg" alt="Twitter icon" />
            </a>
          </li>
          <li>
            <a
              href="#"
              class="flex items-center justify-center w-10 h-10 rounded-full transition-colors duration-300 hover:bg-blue-950"
            >
              <img src="/images/icon-pinterest.svg" alt="Pinterest icon" />
            </a>
          </li>
          <li>
            <a
              href="#"
              class="flex items-center justify-center w-10 h-10 rounded-full transition-colors duration-300 hover:bg-blue-950"
            >
              <img src="/images/icon-instagram.svg" alt="Instagram icon" />
            </a>
          </li>
        </ul>
      </div>
    </div>

    <div
      class="flex flex-col space-y-7 md:flex-row md:gap-[12rem] pt-12 text-center md:text-left"
    >
      <div>
        <h3 class="text-gray-700 pb-5">Our company</h3>
        <ul class="leading-[2rem]">
          <li><a class="hover:underline" href="#">How we work</a></li>
          <li><a class="hover:underline" href="#">Why Insure?</a></li>
          <li><a class="hover:underline" href="#">View plans</a></li>
          <li><a class="hover:underline" href="#">Reviews</a></li>
        </ul>
      </div>
      <div>
        <h3 class="text-gray-700 pb-5">Help me</h3>
        <ul class="leading-[2rem]">
          <li><a class="hover:underline" href="#">FAQ</a></li>
          <li><a class="hover:underline" href="#">Terms of use</a></li>
          <li><a class="hover:underline" href="#">Privacy policy</a></li>
          <li><a class="hover:underline" href="#">Cookies</a></li>
        </ul>
      </div>
      <div>
        <h3 class="text-gray-700 pb-5">Contact</h3>
        <ul class="leading-[2rem]">
          <li><a class="hover:underline" href="#">Sales</a></li>
          <li><a class="hover:underline" href="#">Support</a></li>
          <li><a class="hover:underline" href="#">Live chat</a></li>
        </ul>
      </div>
      <div>
        <h3 class="text-gray-700 pb-5">Others</h3>
        <ul class="leading-[2rem]">
          <li><a class="hover:underline" href="#">Careers</a></li>
          <li><a class="hover:underline" href="#">Press</a></li>
          <li><a class="hover:underline" href="#">Licenses</a></li>
        </ul>
      </div>
    </div>
  </footer>
</template>
