<template>
  <header class="bg-black rounded-full py-0.5 mt-8 flex justify-between pl-8 pr-5 gap-px">
    <ul class="flex items-center cursor-pointer">
      <div class="">
        <li class="pt-2 w-14"><img src="/public/CTF.svg" alt="logo" /></li>
      </div>
      <div class="flex items-center gap-px ml-5">
        <div class="bg-white border-black rounded-lg py-3 px-5 hover:bg-lime-400 hover:text-white">
          <li>Main</li>
        </div>
        <div class="bg-white border-black rounded-lg py-3 px-5 hover:bg-lime-400 hover:text-white">
          <li>Scoreboard</li>
        </div>
        <div class="bg-white border-black rounded-lg py-3 px-5 hover:bg-lime-400 hover:text-white">
          <li>Events</li>
        </div>
      </div>
    </ul>
    <div
      class="flex justify-end items-center gap-4 bg-white rounded rounded-r-lg rounded-l-lg pr-4 pl-4"
      style="width: 100%"
    >
      <div
        class="flex align-items-center gap-1 bg-black text-white px-4 py-1 rounded-3xl cursor-pointer hover:bg-lime-400"
      >
        <p>Log in</p>
        <img src="/public/ic_baseline-person.svg" alt="login logo" />
      </div>

      <div class="flex aalign-items-center gap-1 text-xs font-bold cursor-pointer">
        <div
          class="border rounded-full border-black p-2 hover:bg-lime-400 hover:text-white hover:border-lime-400"
        >
          RU
        </div>
        <div class="border rounded-full border-black p-2 bg-black text-white">US</div>
      </div>
    </div>
  </header>
</template>
