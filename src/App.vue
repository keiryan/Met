<script></script>

<template>
  <div class="w-screen h-screen flex">
    <div class="flex-[3_3_0%] bg-[#E9E9E9] flex flex-col justify-between p-8">
      <header class="flex items-center justify-between">
        <div class="text-3xl w-fit">Met</div>
        <!-- Logo -->
        <div class="w-full flex justify-center">
          <ul class="flex w-full justify-between max-w-md">
            <li class="hover:cursor-pointer">About us</li>
            <li class="hover:cursor-pointer">Shop</li>
            <li class="hover:cursor-pointer">Event</li>
            <li class="hover:cursor-pointer">Contacts</li>
          </ul>
        </div>
      </header>

      <section>
        <h1 class="text-7xl">
          Feel the <br />beauty of <br />luxury
          <span class="font-['scriptina'] text-[#C03310]">Vintage</span>
        </h1>
        <div class="max-w-sm mt-16 mb-8">
          Visit the shop for exquisite vintage prodicts that will not leave
          leave you indifferent.
        </div>

        <button class="bg-[#22464A] text-white py-3 px-20 rounded">
          Go to Shop
        </button>
      </section>

      <!-- Filler for spacing -->
      <div></div>
    </div>

    <div
      class="relative flex-[2_2_0%] bg-red-400 bg-cover bg-center p-12 flex justify-end"
      style="
        background-image: url(/images/aranprime-KbytCpI1i5I-unsplash-2.jpg);
      "
    >
      <button
        class="bg-white rounded py-3 px-6 h-fit transition-all duration-300 ease-in-out hover:bg-transparent hover:text-white hover:border-white border-2"
      >
        Learn More
      </button>
      <div
        class="bg-[#C6492B] absolute top-3/4 -left-12 w-24 h-24 rounded-full flex justify-center items-center"
      >
        <svg width="100" height="100" viewBox="0 0 200 200">
          <path
            id="circlePath"
            fill="none"
            stroke="none"
            d="M100,100 m-75,0 a75,75 0 1,1 150,0 a75,75 0 1,1 -150,0"
          />
          <text font-size="23" text-anchor="middle" fill="#ECECEC">
            <textPath
              xlink:href="#circlePath"
              startOffset="50%"
              method="align"
              side="right"
            >
              KNOW MORE • KNOW MORE • KNOW MORE •
            </textPath>
          </text>
        </svg>

        <div class="absolute">
          <img src="/images/Vintage SVG.svg" width="128" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
