<template>
  <section
    class="relative flex flex-col-reverse md:px-[12rem] bg-blue-950 pb-[8rem] text-white"
  >
    <div
      class="absolute inset-0 bg-[url('./images/bg-pattern-intro-right-mobile.svg')] md:bg-[url('./images/bg-pattern-intro-right-desktop.svg')] bg-no-repeat bg-bottom-right md:bg-top-right md:z-10 pointer-events-none"
    ></div>
    <div
      class="absolute top-[3rem] md:top-[30rem] md:h-[504px] md:w-[200px] inset-0 bg-[url('./images/bg-pattern-intro-left-mobile.svg')] md:bg-[url('./images/bg-pattern-intro-left-desktop.svg')] bg-no-repeat bg-left md:bg-bottom-left md:z-10 pointer-events-none"
    ></div>
    <div
      class="md:pt-[15rem] md:relative z-20 text-center md:text-left px-6 md:px-0"
    >
      <div>
        <h1
          class="text-[2.8rem] md:text-7xl font-bold md:before:content-[''] md:before:absolute md:before:top-[-5rem] md:before:h-1 md:before:w-40 md:before:bg-white max-w-[34rem] relative pt-20 md:pt-0"
        >
          Humanizing your insurance.
        </h1>
      </div>
      <div>
        <p class="max-w-[35rem] text-[16px] py-10">
          Get your life insurance coverage easier and faster. We blend our
          expertise and technology to help you find the plan that’s right for
          you. Ensure you and your loved ones are protected.
        </p>
      </div>
      <a
        class="border-2 border-white hover:bg-white hover:text-black border-solid py-2 px-7"
        href="#"
        >View plans</a
      >
    </div>
    <div class="md:absolute md:right-48 md:top-40 z-0">
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
