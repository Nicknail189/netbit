<template>
  <div
    class="h-[400px] m-0 md:m-4 md:p-3 lg:w-auto shadow-lg rounded bg-white text-[#333] flex justify-center items-start overflow-auto"
  >
    <!-- <h4
      class="body-text text-gray-400 flex flex-col justify-center items-center"
    >
      <icon class="text-[40px]" name="uil:cloud-info" />
      <br />
      Transaction history will appear here
    </h4> -->

    <!-- <table>
      <tr>
        <th>Alert</th>
        <th>Percentage Increase</th>
        <th>Amount</th>
        <th></th>
        <th></th>
      </tr>
      <tr>
        <td><img src="/candle.svg" alt="" /></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
    </table> -->

    <div
      style="
        height: 560px;
        background-color: #ffffff;
        overflow: hidden;
        box-sizing: border-box;
        border: 1px solid #56667f;
        border-radius: 4px;
        text-align: right;
        line-height: 14px;
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
      <div style="height: 540px; padding: 0px; margin: 0px; width: 100%">
        <iframe
          src="https://widget.coinlib.io/widget?type=chart&theme=light&coin_id=859&pref_coin_id=1505"
          width="100%"
          height="536px"
          scrolling="auto"
          marginwidth="0"
          marginheight="0"
          frameborder="0"
          border="0"
          style="border: 0; margin: 0; padding: 0; line-height: 14px"
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
</template>



<style scoped>
table,
th,
td {
  text-align: center;
  padding: 4px 10px;
  border: solid 0.3px #8080802a;
}

th {
  color: #182565;
}
</style>