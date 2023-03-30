<template>
  <div class="flex flex-col lg:flex-row">
    <!-- card one -->
    <div class="container bg-[#685539]">
      <h2 class="medium-header">Premium Account</h2>
      <br />
      <p class="body-text">
        Premium members earn more and access exclusive features across the
        platform.
      </p>
    </div>

    <!-- card two -->
    <div class="container bg-[#161d34]">
      <h2 class="medium-header">Guest</h2>
      <br />
      <p class="body-text">
        A guest has a limited access to a visiting account. To open an account
        with NETBIT, Contact your referer. Premium Account comes with top tier
        security system.
      </p>
    </div>

    <!-- card three -->
    <NuxtLink
      to="https://youtu.be/Yb6825iv0Vk"
      class="container bg-[#512828] flex flex-col items-center justify-center"
    >
      <button class="body-text py-2 px-3 flex items-center border rounded-md">
        <icon class="mr-2 text-[20px]" name="uil:play-circle" />
        LEARN MORE
      </button>
      <p class="body-text mt-2">Learn more about crypto - for beginners</p>
    </NuxtLink>
  </div>
</template>