<template>
  <div class="h-auto md:p-5 w-full">
    <div class="w-full fixed top-0 z-40 left-0 right-0">
      <div
        style="
          height: 62px;
          background-color: #ffffff;
          overflow: hidden;
          box-sizing: border-box;
          border: 1px solid #56667f;
          border-radius: 4px;
          text-align: right;
          line-height: 14px;
          block-size: 62px;
          font-size: 12px;
          font-feature-settings: normal;
          text-size-adjust: 100%;
          box-shadow: inset 0 -20px 0 0 #56667f;
          padding: 1px;
          padding: 0px;
          margin: 0px;
          width: 100%;
        "
      >
        <div style="height: 40px; padding: 0px; margin: 0px; width: 100%">
          <iframe
            src="https://widget.coinlib.io/widget?type=horizontal_v2&theme=light&pref_coin_id=1505&invert_hover="
            width="100%"
            height="36px"
            scrolling="auto"
            marginwidth="0"
            marginheight="0"
            frameborder="0"
            border="0"
            style="border: 0; margin: 0; padding: 0"
          ></iframe>
        </div>
        <div
          style="
            color: #ffffff;
            line-height: 14px;
            font-weight: 400;
            font-size: 11px;
            box-sizing: border-box;
            padding: 2px 6px;
            width: 100%;
            font-family: Verdana, Tahoma, Arial, sans-serif;
          "
        >
          <a
            href="https://coinlib.io"
            target="_blank"
            style="
              font-weight: 500;
              color: #ffffff;
              text-decoration: none;
              font-size: 11px;
            "
            >Cryptocurrency Prices</a
          >&nbsp;by NETBIT
        </div>
      </div>
    </div>
    <div class="mt-14">
      <!-- side bar call button -->
      <div
        @click="dashboard()"
        class="md:hidden fixed right-[20px] bottom-[40px] w-10 h-10 bg-black flex justify-center items-center"
      >
        <icon class="text-[30px]" name="uil:create-dashboard" />
      </div>

      <div class="flex w-full h-full">
        <!-- side bar -->
        <div
          id="side-bar"
          class="fixed left-[-1000px] md:sticky w-full md:w-auto"
        >
          <NuxtLink to="/">
            <navigation />
          </NuxtLink>
          <side-bar @close-sidebar="closedashboard()" />
        </div>
        <!-- dashboard content -->
        <div class="flex flex-col w-full">
          <div class="flex flex-col lg:flex-row items-start">
            <db-personal-info />
            <amount />
          </div>
          <div>
            <db-cards />
          </div>
          <div>
            <transactions />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    methods: {
      dashboard(){
        document.getElementById('side-bar').style.left = '0px'
      },
      closedashboard(){
        document.getElementById('side-bar').style.left = '-1000px'
      }
    }
}
</script>