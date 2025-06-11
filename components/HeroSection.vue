<template>
  <section class="relative flex md:px-[12rem] bg-blue-950 pb-[8rem] text-white">
    <div
      class="absolute inset-0 bg-[url('./images/bg-pattern-intro-right-desktop.svg')] bg-no-repeat bg-top-right z-10 pointer-events-none"
    ></div>
    <div
      class="absolute top-[30rem] h-[504px] w-[200px] inset-0 bg-[url('./images/bg-pattern-intro-left-desktop.svg')] bg-no-repeat bg-bottom-left z-10 pointer-events-none"
    ></div>
    <div class="pt-[15rem] relative z-20">
      <h1
        class="text-7xl font-bold before:content-[''] before:absolute before:top-[-5rem] before:h-1 before:w-40 before:bg-white max-w-[34rem] relative"
      >
        Humanizing your insurance.
      </h1>
      <p class="max-w-[35rem] text-[16px] py-10">
        Get your life insurance coverage easier and faster. We blend our
        expertise and technology to help you find the plan that’s right for you.
        Ensure you and your loved ones are protected.
      </p>
      <a
        class="border-2 border-white hover:bg-white hover:text-black border-solid py-2 px-7"
        href="#"
        >View plans</a
      >
    </div>
    <div class="absolute right-48 top-40 z-0">
      <figure>
        <picture>
          <source
            srcset="/images/image-intro-mobile.jpg"
            media="(max-width: 768px)"
          />
          <img src="/images/image-intro-desktop.jpg" alt="Introduction" />
        </picture>
      </figure>
    </div>
  </section>
</template>
