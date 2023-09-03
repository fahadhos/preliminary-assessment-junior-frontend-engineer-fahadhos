<svelte:head>
  <link
    href="https://cdn.jsdelivr.net/npm/daisyui@1.16.2/dist/full.css"
    rel="stylesheet"
    type="text/css"
  />
  <link
    href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2/dist/tailwind.min.css"
    rel="stylesheet"
    type="text/css"
  />
</svelte:head>

<!-- navbar start -->
<div class="navbar bg-base-100">
  <div class="navbar-start">
    <div class="dropdown">
      <!-- svelte-ignore a11y-positive-tabindex -->
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <!-- svelte-ignore a11y-label-has-associated-control -->
      <label tabindex="0" class="btn btn-ghost btn-circle">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          ><path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h7"
          /></svg
        >
      </label>
      <!-- svelte-ignore a11y-positive-tabindex -->
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <ul
        tabindex="0"
        class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52"
      >
        <li><a href="/">Homepage</a></li>
        <li><a href="map">Map</a></li>
        <li><a href="chart">Chart</a></li>
      </ul>
    </div>
  </div>
  <div class="navbar-center">
    <a href="/" class="btn btn-ghost normal-case text-xl">Svelte App</a>
  </div>
  <div class="navbar-end">
    <button class="btn btn-ghost btn-circle">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        class="h-5 w-5"
        fill="none"
        viewBox="0 0 24 24"
        stroke="currentColor"
        ><path
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
        /></svg
      >
    </button>
    <button class="btn btn-ghost btn-circle">
      <div class="indicator">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          ><path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
          /></svg
        >
        <span class="badge badge-xs badge-primary indicator-item" />
      </div>
    </button>
  </div>
</div>
<!-- Navbar -->
<!-- Layout page max-sm:grid-cols-4 max-sm:grid-rows-6  -->
<div
  class="lg:grid  lg:grid-cols-12 lg:grid-rows-6 max-sm:hidden  max-w-screen-2xl lg:gap-0 col-gap-0 lg:gap-x-0 lg:mx-auto lg:my-0"
>
  <!-- 3x2 blue-400 -->
  <div
    class="col-span-2 row-span-3 gap-x-0 bg-blue-400 w-[256px] h-[290.01px]"
  >
    <!-- <div class=" ">3 × 2</div> -->
  </div>
  <!-- 2x2 color teal-400 -->
  <div
    class="col-span-2 row-span-2 col-start-1 row-start-4 gap-x-0 bg-teal-400 w-[256px] h-[193.34px]"
  >
    <!-- <div class="">2 × 2</div> -->
  </div>
  <!-- 1x6  fuchsia-400 -->
  <div
    class="col-span-6 col-start-1 row-start-6 gap-x-0 bg-fuchsia-400 w-[778px] h-[96.67px]"
  >
    <!-- <div class="">1 × 6</div> -->
  </div>
  <!-- 4x2 emerald-400 -->
  <div
    class="col-span-2 row-span-4 col-start-11 row-start-3 gap-x-0 bg-emerald-400 max-w  h-[386.68px]"
  >
    <!-- <div class="artboard">4 × 2</div> -->
  </div>
  <!-- 4x4 yellow-100 -->
  <div
    class="col-span-4 row-span-4 col-start-7 row-start-3 gap-x-0 bg-yellow-100 w-[515px] h-[386.68px] justify-center items-center mx-auto my-0 py-12"
  >
    <!-- mountain thakbe -->
    <div class="square mx-auto my-0 w-[300px] h-[100px]">
      <div class="hole bg-yellow-100 -ml-1">
        <div class="box relative top-[9.1rem] left-[4.2rem]" />
        <div class="triangle relative top-[6.3rem] left-100" />
      </div>
    </div>
    <!-- <div class="triangle"></div> -->
    <!-- <div class="artboard">4 × 4</div> -->
  </div>
  <!-- 2x6 blue-400 -->
  <div
    class="col-span-6 row-span-2 col-start-7 row-start-1 gap-x-0 bg-blue-400 max-w  h-[193.34px]"
  >
    <!-- <div class="artboard">2 × 6</div> -->
  </div>
  <!-- 5x4 color rose-100 -->
  <div
    class="col-span-4 row-span-5 col-start-3 row-start-1 gap-x-0 bg-rose-100 max-w h-[483.35px]"
  >
    <!-- <div class="artboard ">5 × 4</div> -->
  </div>
</div>

<!-- layout -->
<!-- layout for mobile -->

<div class="lg:hidden max-sm:grid max-sm:grid-cols-4  max-sm:grid-rows-6 max-sm:gap-0">
    <div class="col-span-4 row-span-3  bg-rose-100 w-[425px] h-[483.35px]">


    </div>
    <div class="col-span-4 row-span-3 row-start-4  bg-yellow-100 w-[425px] h-[386.68px] justify-center items-center mx-auto my-0 py-12">

  <!-- mountain thakbe -->
  <div class="square mx-auto my-0 w-[300px] h-[100px]">
    <div class="hole bg-yellow-100">
        <div class="box relative top-[9.1rem] left-[4.2rem]" />
        <div class="triangle relative top-[6.3rem] left-100" />
    </div>
  </div>
    </div>
</div>
    
<!-- layout for mobile -->
<style>
  .box {
    width: 0;
    height:0;
    border-left: 34px solid transparent;
    border-right: 50px solid transparent;
    border-bottom: 90px solid #fe5f55;

    border-radius: 0% 0% 50% 58%;
    position: absolute;
  }
  .triangle {
    width: 0;
    height: 0;
    border-left: 110px solid transparent;
    border-right: 61px solid transparent;
    border-bottom: 150px solid #fe5f55;
    /* border-top: 120px solid #fe5f55; */
    border-radius: 0% 0% 200% 200%;
    position: absolute;
    bottom: 0px;
    left: 0;
    right: 0;
    margin: 0 auto;
    /* border-bottom-right-radius: 0.5rem/* 8px */
    /* border-bottom-left-radius: 0.5rem   */
  }

  .hole {
    width: 200px;
    height: 200px;
    background-color: rgb(254, 249, 195);
    border: 2px solid #293462;
    border-radius: 50%;
    /* z-index: 1000; */

    /* z-index: inherit; */
  }

  .square {
    width: 300px;
    height: 300px;
    background-color: #293462;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
  }
</style>
