<template>
  <div class="flex flex-col lg:flex-row">
    <!-- card one -->
    <div class="container bg-[#685539] flex flex-col justify-center items-center overflow-hidden">
    <div class="max-w-[200px] max-h-[200px]">
    <img class="rounded-md hover:shadow-xl" src="/premium.jpg"/>
    </div>
    <div class="mt-6">
      <h2 class="medium-header leading-[5px]">Premium Account</h2>
      <br />
      <p class="body-text">
        Premium members earn more and access exclusive features across the
        platform.
      </p>
    </div>
    </div>

    <!-- card two -->
    <div class="container bg-[#161d34] flex flex-col justify-center items-center overflow-hidden">
        <div class="max-w-[200px] max-h-[200px]">
    <img class="rounded-md" src="/security.jpg"/>
    </div>
    <div class="mt-6">
      <h2 class="medium-header leading-[5px]">Guest</h2>
      <br />
      <p class="body-text">
        A guest has a limited access to a visiting account. To open an account
        with NETBIT, Contact your referer. Premium Account comes with top tier
        security system.
      </p>
      </div>
    </div>

    <!-- card three -->
    <NuxtLink
      to="https://youtu.be/Yb6825iv0Vk"
      class="container bg-[#512828] flex flex-col items-center justify-center"
    >
    <div class="max-w-[200px] max-h-[200px]">
    <img class="rounded-md" src="/learning.jpg"/>
    </div>
      <button class="body-text py-2 px-3 flex items-center border rounded-md">
        <icon class="mr-2 text-[20px]" name="uil:play-circle" />
        LEARN MORE
      </button>
      <p class="body-text mt-2">Learn more about crypto - for beginners</p>
    </NuxtLink>
  </div>
</template>