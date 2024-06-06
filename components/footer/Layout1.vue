<script setup lang="ts">
const scrollToTop = () => {
  window.scrollTo({
    top: 0,
    behavior: "smooth"
  });
}
</script>

<template>
  <footer id="footer-3" class="pt-100  footer ft-3-ntr"
    style="direction: rtl;background-image: url(https://png.pngtree.com/thumb_back/fw800/back_our/20190622/ourmid/pngtree-olive-oil-skin-care-essential-oil-banner-background-image_232190.jpg); background-position: center;background-size: cover;">
    <div class="container">
      <!-- FOOTER CONTENT -->
      <div class="flex flex-col lg:flex-row items-center gap-10 lg:gap-40">
        <NuxtLink to="/">
          <img class="w-48" src="/assets/images/logo.png" alt="footer-logo"  @click="scrollToTop()">
        </NuxtLink>
        <div class="flex items-center gap-10 md:gap-20">
          <nuxt-link to="/" class="text-white hover:underline text-md md:text-2xl cursor-pointer" @click="scrollToTop()">الرئيسية</nuxt-link>
          <nuxt-link to="/products" class="text-white hover:underline text-md md:text-2xl cursor-pointer">المنتجات</nuxt-link>
          <nuxt-link to="/about" class="text-white hover:underline text-md md:text-2xl cursor-pointer">من نحن</nuxt-link>
          <nuxtLink to="/contact" class="text-white hover:underline text-md md:text-2xl cursor-pointer">تواصل معنا</nuxtLink>

        </div>
      </div>

      <!-- END FOOTER CONTENT -->
      <hr>
      <!-- FOOTER DIVIDER LINE -->
      <!-- BOTTOM FOOTER -->
      <div class="bottom-footer">
        <div class="flex flex-col-reverse gap-2 md:flex-row items-center">
          <!-- FOOTER COPYRIGHT -->
          <div>
            <div class="footer-copyright text-white text-xl">
              <p class="p-sm">
                <span>All Rights Reserved By <NuxtLink class="font-bold text-xl text-pink-500 mx-1" target="_blank"
                    to="https://www.skylink-eg.com/">Skylink</NuxtLink></span> &copy; 2024
              </p>
            </div>
          </div>
          <div class=" mx-auto text-center">
            <h1 class="text-white text-xl">Mail us : <NuxtLink class="underline cursor-pointer text-blue-700 font-bold"
                to="">info@elsalamoil.com</NuxtLink>
            </h1>
          </div>

          <!-- FOOTER SOCIALS -->
          <div>
            <ul class="flex items-center gap-2">
              <li>
                <a href="https://facebook.com" target="_blank"><span class="flaticon-facebook text-white" /></a>
              </li>
              <li>
                <a href="#"><span class="flaticon-twitter text-white" /></a>
              </li>
              <li>
                <a href="#"><span class="flaticon-instagram text-white" /></a>
              </li>
              <li>
                <a href="#"><span class="flaticon-youtube text-white" /></a>
              </li>
            </ul>
          </div>
        </div>
        <!-- End row -->
      </div>
      <!-- END BOTTOM FOOTER -->
    </div>
    <!-- End container -->
    <FooterGoToTop />
  </footer>
</template>
