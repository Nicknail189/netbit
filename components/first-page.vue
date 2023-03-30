<template>
  <div
    class="h-screen w-full md:grid md:grid-cols-3 flex flex-col justify-center items-center"
  >
    <div
      class="hidden md:block relative md:col-span-2 bg-[url('/firstpage-img.jpg')] bg-cover"
    >
      <div class="bg-[#182565de] w-full h-screen p-20">
        <!-- company logo -->
        <div
          class="z-40 bg-white inline-flex items-center p-3 text-[#333] text-[30px] font-extrabold"
        >
          <img
            class="w-10 h-10 mr-4"
            src="/bitcoin-network-symbol.png"
            alt="company-logo"
          />
          NETBIT
        </div>

        <!-- text -->
        <div class="z-40">
          <h2 class="large-header leading-[60px] mt-4">NETBIT</h2>
          <h4 class="medium-header mt-5 uppercase">
            Creating wealth investing in crypto currencies
          </h4>
          <br />
          <p class="w-8/12">
            Invest, borrow, and spend on one intuitive platform. Customize your
            strategies, automate the big picture, and let The Finance Super App®
            take care of the day-to-day—commission-free.
            <br />
            <br />
            What is Bitcoin? Bitcoin is a digital currency, also known as a
            cryptocurrency, and is created or mined when people solve complex
            math puzzles online. These bitcoins are then stored in a digital
            wallet that exists on the cloud or the user’s computer.
            <br />
            <br />
            We are a technology-first company that utilizes the latest in
            information security.
            <br />
            Member of SIPC. Securities in your account protected up to $500,000.
            For details, please see
            <a
              class="underline"
              href="https://www.sipc.org/"
              target="_blank"
              rel="noreferrer noopener"
              >www.sipc.org</a
            >.
          </p>
          <br />
          <br />
          <br />
          <div class="flex items-center justify-between">
            <icon class="text-[40px]" name="uil:bitcoin" />
            <icon class="w-10/12" name="uil:arrows-h" />
            <icon class="text-[40px]" name="uil:money-stack" />
          </div>
        </div>
      </div>
    </div>

    <div class="flex flex-col justify-center items-center gap-4">
      <div
        class="z-40 rounded-md mb-20 bg-white inline-flex items-center text-[#333] text-[30px] p-3 md:hidden"
      >
        <img
          class="w-10 h-10 mr-4"
          src="/bitcoin-network-symbol.png"
          alt="company-logo"
        />
        NETBIT
      </div>
      <NuxtLink to="/signUpPage">
        <button class="login-btn">Sign up</button>
      </NuxtLink>
      <NuxtLink to="/signInPage">
        <button class="login-btn">Sign in</button>
      </NuxtLink>
    </div>
  </div>
</template>