<template>
  <header class="flex justify-between px-5 pt-5">
    <div class="w-52 flex items-center">
      <img class="w-full object-cover" :src="logo" alt="Logo" />
    </div>
    <div class="hidden md:flex gap-5 mr-32">
      <p class="text-2xl hover:text-blue-700 cursor-pointer">main</p>
      <p class="text-2xl hover:text-blue-700 cursor-pointer">news</p>
      <p class="text-2xl hover:text-blue-700 cursor-pointer">team</p>
    </div>
    <div class="w-8 h-1 flex items-center mt-2 md:hidden">
      <img class="w-full" :src="barsSolid" alt="" />
    </div>
  </header>
  <main class="mt-10">
    <div class="relative overflow-hidden">
      <div class="h-screen">
        <img class="h-full w-full object-cover" :src="banner" alt="banner" />
      </div>
      <div class="w-full flex justify-center">
        <div
          class="py-10 px-12 absolute top-0 mt-10 opacity-40 bg-slate-50 rounded-3xl md:left-28 top-96 px-32"
        >
          <p class="text-5xl text-black md:text-6xl">
            сокровище <br />
            нации
          </p>
        </div>
      </div>
      <div class="absolute bottom-11 ml-11 flex gap-4 md:bottom-56 ml-28">
        <img class="w-10 md:w-16" :src="play" alt="" />
        <p class="text-white text-2xl md:text-4xl mt-1">видео проектa</p>
      </div>
    </div>
    <div>
      <div class="flex w-full">
        <img class="w-96 h-96" :src="first - image - 1" alt="" />
        <div>
          <p>Геймлей будет осуществлен в 2D Комиксе, с плавными переходами</p>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import LOGO from "./assets/LOGO.png";
import BANNER from "./assets/BANNER.png";
import barsSolid from "./assets/barsSolid.png";
import play from "./assets/play.png";

export default {
  data() {
    return {
      logo: LOGO,
      banner: BANNER,
      barsSolid: barsSolid,
      play: play,
    };
  },
};
</script>
