<template>
  <header class="flex justify-between px-5 pt-5">
    <div class="w-52 flex items-center">
      <img class="w-full object-cover" :src="logo" alt="Logo" />
    </div>
    <div class="hidden md:flex gap-5 mr-32">
      <p class="text-2xl hover:text-blue-700 cursor-pointer">Главное</p>
      <p class="text-2xl hover:text-blue-700 cursor-pointer">Новости</p>
      <p class="text-2xl hover:text-blue-700 cursor-pointer">Команда</p>
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
    <div class="flex w-full gap-12 mb-12 mt-16 px-48 justify-center">
      <div class="w-1/2 flex justify-end">
        <img class="w-2/3" :src="gameplay1" alt="" />
      </div>
      <div class="w-1/2 flex items-center">
        <p class="text-xl">
          Геймлей будет осуществлен в 2D <br />
          Комиксе, с плавными переходами
        </p>
      </div>
    </div>

    <hr class="w-11/12 mx-auto border border-black" />

    <div class="flex w-full gap-12 my-12 px-48 justify-center">
      <div class="w-1/2 flex text-end items-center">
        <p class="text-xl">
          Предназначение игры заключается в знакомстве игрока с национальной
          культурой, одеждой и языка регионов Российской Федерацией и Дружбой
          Народов России. На выбор даются все национальные регионы, игрок может
          выбрать как свой регион, так и другие регионы
        </p>
      </div>
      <div class="w-1/2 flex justify-start">
        <img class="w-2/3" :src="gameplay2" alt="" />
      </div>
    </div>

    <hr class="w-11/12 mx-auto border border-black" />

    <div class="flex w-full gap-12 my-12 px-48 justify-center">
      <div class="w-1/2 flex justify-end">
        <img class="w-2/3" :src="gameplay3" alt="" />
      </div>
      <div class="w-1/2 flex text-start items-center">
        <p class="xl">
          Тематический сюжетный раннер, обучающий национальным языкам через
          геймплей игры для детей дошкольного и школьного возраста.
        </p>
      </div>
    </div>

    <hr class="w-11/12 mx-auto border border-black" />

    <div class="flex w-full gap-12 my-12 px-48 justify-center">
      <div class="w-1/2 flex text-end items-center">
        <p class="xl">
          Двое детей (мальчик и девочка) играют в доме бабушки, случайно находят
          на чердаке изрядно потрепанную книгу. С этого и начинается их история
        </p>
      </div>
      <div class="w-1/2 flex justify-start">
        <img class="w-2/3" :src="gameplay4" alt="" />
      </div>
    </div>

    <div class="bg-gray-950 gap-10 w-screen flex overflow-x-auto">
      <p class="3xl">ГАЛЕРЕЯ</p>
      <img class="w-1/5" :src="scrollImage1" alt="" />
      <img class="w-1/5" :src="scrollImage2" alt="" />
      <img class="w-1/5" :src="scrollImage3" alt="" />
      <img class="w-1/5" :src="scrollImage4" alt="" />
      <img class="w-1/5" :src="scrollImage5" alt="" />
      <img class="w-1/5" :src="scrollImage6" alt="" />
    </div>
  </main>
</template>

<script>
import LOGO from "./assets/LOGO.png";
import BANNER from "./assets/BANNER.png";
import barsSolid from "./assets/barsSolid.png";
import play from "./assets/play.png";
import gameplay1 from "./assets/gameplay1.jpg";
import gameplay2 from "./assets/gameplay2.jpg";
import gameplay3 from "./assets/gameplay3.jpg";
import gameplay4 from "./assets/gameplay4.jpg";
import scrollImage1 from "./assets/scrollImage1.png";
import scrollImage2 from "./assets/scrollImage2.png";
import scrollImage3 from "./assets/scrollImage3.jpg";
import scrollImage4 from "./assets/scrollImage4.jpg";
import scrollImage5 from "./assets/scrollImage5.png";
import scrollImage6 from "./assets/scrollImage6.png";

export default {
  data() {
    return {
      logo: LOGO,
      banner: BANNER,
      barsSolid: barsSolid,
      play: play,
      gameplay1: gameplay1,
      gameplay2: gameplay2,
      gameplay3: gameplay3,
      gameplay4: gameplay4,
      scrollImage1: scrollImage1,
      scrollImage2: scrollImage2,
      scrollImage3: scrollImage3,
      scrollImage4: scrollImage4,
      scrollImage5: scrollImage5,
      scrollImage6: scrollImage6,
    };
  },
};
</script>
