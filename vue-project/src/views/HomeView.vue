<template>
  <div>
    <DestCard
      v-for="destination in destinations"
      :key="destination.name"
      :Destination="destination"
    />
  </div>
</template>

<script setup>
import DestCard from "@/components/DestCard.vue";
const destinations = [
  {
    name: "KD 15 B.A.D",
    International: true,
    price: 1300,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20221229/106eca26736945d2a1db9d5321865a7c.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "Jordan 4 Seafoam",
    International: true,
    price: 800,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20230528/ff23aa7eff334ec5902dc0e588403f67.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "GT Cut 2 Easter",
    International: true,
    price: 1200,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20230526/b372e4cb6eea4ca1b7fe7952a107797a.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "Jordan 1 Reverse Mocha",
    International: false,
    price: 900,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20230528/373224f4eb5e47fea4f38e1c15bffd00.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "Kyrie Low 5 Nets",
    International: false,
    price: 400,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20220722/33c57b0750e345dfa57fdd6f1324f320.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "Kyrie 5 Mom White",
    International: true,
    price: 600,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20220212/d422bde2860f43e3bb456bdb572461a1.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: " GT Cut 1 Think Pink",
    International: true,
    price: 800,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20230526/4fedd830400f48c1be8cc2618647e1b6.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "Kyrie Low 4 Kay Yow",
    International: true,
    price: 800,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20230211/538ded8aa8d34f4f84f7b6f1aec8835a.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "Jordan 4 Off-White Sail",
    International: true,
    price: 800,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20230528/d10ce095c253415890a8a4835eb26213.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "PG 6 Painted Swoosh",
    International: true,
    price: 800,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20220815/9c0c56eda35d455d91730b242842d086.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "KD 14 Aquafresh",
    International: true,
    price: 800,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20220212/f026358b6bb1407d8ec453b37ceb3f9e.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
  {
    name: "Kobe 6 Protro Mambacita",
    International: true,
    price: 800,
    img: "https://cdn-img.poizonapp.com/pro-img/cut-img/20220428/8e6f51bea872465aac88b03ca5f182c0.jpg?x-oss-process=image/format,webp/resize,w_800",
  },
];
</script>

<style scoped></style>