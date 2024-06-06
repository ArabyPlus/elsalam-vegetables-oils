<template>
    <swiper
      :pagination="{
        type: 'fraction',
      }"
      :navigation="true"
      :speed="800"

      :autoplay="{ delay: 3000 }"
      :modules="modules"
      class="mySwiper swiper rounded-xl"
    >
      <swiper-slide ><img  src="/assets/images/elsalam/about.jpg" alt=""></swiper-slide>
      <swiper-slide ><img  src="/assets/images/elsalam/contact.jpg" alt=""></swiper-slide>
      <swiper-slide ><img  src="/assets/images/elsalam/img-8.jpg" alt=""></swiper-slide>
      <swiper-slide ><img  src="/assets/images/elsalam/0J6A1786.jpg" alt=""></swiper-slide>
      <swiper-slide ><img  src="/assets/images/elsalam/0J6A1996.jpg" alt=""></swiper-slide>
      <swiper-slide ><img  src="/assets/images/elsalam/0J6A2023.jpg" alt=""></swiper-slide>
    </swiper>
  </template>
  
  <script setup>
  import { Swiper, SwiperSlide } from 'swiper/vue'
  import 'swiper/css'
  import 'swiper/css/pagination'
  import 'swiper/css/navigation'
  
  import { Pagination, Navigation, Autoplay } from 'swiper/modules'
  
  const modules = [Pagination, Navigation, Autoplay]
  </script>
  
  <style scoped>
  #app {
    height: 100%;
  }
  html,
  body {
    position: relative;
    height: 100%;
  }
  
  body {
    background: #eee;
    font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 14px;
    color: #000;
    margin: 0;
    padding: 0;
  }
  
  .swiper {
    width: 70%;
    height: 70%;
    border-radius: 10px;
  }
  
  .swiper-slide {
    text-align: center;
    font-size: 18px;
    background: #fff;
  
    /* Center slide text vertically */
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .swiper-slide img {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  </style>
  