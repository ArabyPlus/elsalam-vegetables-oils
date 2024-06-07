<template>
    <div id="main-menu" class="wsmainfull menu clearfix scroll scroll">
        <div class="wsmainwp clearfix scroll flex items-center justify-between">
            <!-- HEADER BLACK LOGO -->
            <div class="desktoplogo">
                <NuxtLink to="/" class="logo-black"><img src="/assets/images/elsalam/logo.png" alt="logo" /></NuxtLink>
            </div>
            <!-- HEADER WHITE LOGO -->
            <div class="desktoplogo">
                <NuxtLink to="/" class="logo-white"><img src="/assets/images/elsalam/logo.png" alt="logo" /></NuxtLink>
            </div>
            <!-- MAIN MENU -->
            <nav class="wsmenu clearfix scroll">
                <ul class="wsmenu-list nav-theme ">
                    <!-- DROPDOWN SUB MENU -->

                    <li class="mg_link">
                        <NuxtLink to="/contact-us" class="h-link hover:bg-orange-400 rounded w-fit ">تواصل معنا </NuxtLink>

                        <!-- End wsmegamenu -->
                    </li>
                    <!-- END MEGAMENU -->
                    <!-- SIMPLE NAVIGATION LINK -->
                    <li class="" aria-haspopup="true">
                        <NuxtLink to="/about-us" class="h-link hover:bg-orange-400 rounded w-fit "  >من نحن</NuxtLink>
                    </li>
                    <!-- SIMPLE NAVIGATION LINK -->
                    <li class="nl-simple" aria-haspopup="true">
                        <NuxtLink to="/products" class="h-link hover:bg-orange-400 rounded w-fit ">المنتجات</NuxtLink>
                    </li>
                    <li class="nl-simple" aria-haspopup="true">
                        <NuxtLink to="/" class="h-link hover:bg-orange-400 rounded w-fit ">الرئيسية</NuxtLink>
                    </li>
                    <li class="mx-4" >
                        <HeaderDarkLightToggle class="" />
                    </li>
                    <!-- SIGN IN LINK -->
                    <!-- SIGN UP BUTTON -->
                </ul>
            </nav>
            <!-- END MAIN MENU -->
        </div>
    </div>
</template>
<script>
import { reactive } from 'vue';
export default {
    setup() {
        const state = reactive({
            isOpen: [false, false]
        });
        const toggle = (index) => {
            state.isOpen[index] = !state.isOpen[index];
        };
        return {
            toggle,
            isOpen: state.isOpen
        };
    },
    mounted() {
        window.addEventListener("scroll", this.handleScroll);
    },
    destroyed() {
        window.removeEventListener("scroll", this.handleScroll);
    },
    methods: {
        handleScroll() {
            const menu = document.getElementById("main-menu");
            const header = document.getElementById("header");
            if (window.pageYOffset > 100) {
                menu.classList.add("scroll");
                header.classList.add("scroll");
            } else {
                menu.classList.remove("scroll");
                header.classList.remove("scroll");
            }
        }
    }
};
</script>
<style scoped>
.h-link{
    color: rgb(7, 180, 65) !important;
}
</style>