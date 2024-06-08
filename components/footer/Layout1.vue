<template>
    <footer id="footer-3" class="pt-100 footer ft-3-ntr text-white"
    style="direction: rtl;background-image: url(https://5alfiat.com/wp-content/uploads/2023/03/7%D8%AE%D9%84%D9%81%D9%8A%D8%A7%D8%AA-%D8%AE%D8%B6%D8%B1%D8%A7%D8%A1.jpg); background-position: center;background-size: cover;">
        <div class="container text-white">
            <!-- FOOTER CONTENT -->
            <div class="row text-white">
                <!-- FOOTER LOGO -->
                
                <!-- FOOTER LINKS -->
               <div class="flex flex-col md:flex-row items-center justify-around">
                <div class="footer-info">
                        <img class="footer-logo" src="/assets/images/elsalam/logo.png" alt="footer-logo" />
                    </div>
                <div >
                    <div class="footer-links fl-1">
                        <!-- Title -->
                        <nuxt-link to="/" class="text-white hover:bg-orange-400 text-center px-4 py-2 rounded text-md md:text-2xl cursor-pointer " @click="scrollToTop()" >الرئيسية</nuxt-link>
                        <!-- Links -->
                       
                    </div>
                </div>
                <!-- END FOOTER LINKS -->
                <!-- FOOTER LINKS -->
                <div >
                    <div class="footer-links fl-2">
                        <!-- Title -->
                        <nuxt-link to="/products" class="text-white hover:bg-orange-400 text-center px-4 py-2 rounded text-md md:text-2xl cursor-pointer">المنتجات</nuxt-link>
                        <!-- Links -->
                        
                    </div>
                </div>
                <!-- END FOOTER LINKS -->
                <!-- FOOTER LINKS -->
                <div >
                    <div class="footer-links fl-3">
                        <!-- Title -->
                        <nuxt-link to="/about-us" class="text-white hover:bg-orange-400 text-center px-4 py-2 rounded text-md md:text-2xl cursor-pointer">من نحن</nuxt-link>
                        <!-- Links -->
                        
                    </div>
                </div>
                <div >
                    <div class="footer-links fl-3">
                        <!-- Title -->
                        <nuxtLink to="/contact-us" class="text-white hover:bg-orange-400 text-center px-4 py-2 rounded text-md md:text-2xl cursor-pointer">تواصل معنا</nuxtLink>
                        <!-- Links -->
                        
                    </div>
                </div>

               </div>
                <!-- END FOOTER LINKS -->
                <!-- FOOTER NEWSLETTER FORM -->
                
                <!-- END FOOTER NEWSLETTER FORM -->
            </div>
            <!-- END FOOTER CONTENT -->
            <hr />
            <!-- FOOTER DIVIDER LINE -->
            <!-- BOTTOM FOOTER -->
            <div class="bottom-footer">
               
                    <!-- FOOTER COPYRIGHT -->
                   
                    <!-- FOOTER SOCIALS -->
                    <div class="flex flex-col md:flex-row items-center justify-between gap-4">
                        <div >
                            <span class="p-sm flex items-center justify-center mx-auto text-center gap-1">&copy; 2024 <nuxt-link class="cursor-pointer" target="_blank" to="https://www.skylink-eg.com/">
                                <img class="rounded w-40" src="https://www.skylink-eg.com/images/logo.png" alt=""></nuxt-link>  <span>All Rights Reserved</span> </span>
                        </div>
                        <h1 class="text-white text-xl">Mail us : <span class="underline cursor-pointer text-orange-500 hover:text-orange-600 font-bold"
                to="">info@elsalamoil.com</span>
            </h1>                        <ul class="flex gap-2 justify-end">
                            <li>
                                <a href="#"><span class="flaticon-facebook text-white"></span></a>
                            </li>
                            <li>
                                <a href="#"><span class="flaticon-twitter text-white"></span></a>
                            </li>
                            <li>
                                <a href="#"><span class="flaticon-instagram text-white"></span></a>
                            </li>
                            <li>
                                <a href="#"><span class="flaticon-youtube text-white"></span></a>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- End row -->
           
            <!-- END BOTTOM FOOTER -->
        </div>
        <!-- End container -->
        <FooterGoToTop />
    </footer>
</template>

<script setup>
const scrollToTop = () => {
  window.scrollTo({ top: 0, behavior: 'smooth' })
}
</script>
