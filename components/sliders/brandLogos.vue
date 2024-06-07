<template>
    <div class="brands-carousel-5">
        <Swiper
            :modules="[SwiperAutoplay, SwiperEffectCreative]"
            :slides-per-view="2"
            :loop="true"
            :autoplay="{
                delay: 8000,
                disableOnInteraction: true
            }"
            :breakpoints="{
                400:{ slidesPerView:2 },
                600:{ slidesPerView:3 },
                900:{ slidesPerView:4, },
                1024:{ slidesPerView:5, },
            }"
        >
            <SwiperSlide>
                <div class="brand-logo">
                    <img class="img-fluid theme-light" src="/assets/images/elsalam/0J6A1786.jpg" alt="brand-logo" />
                    <img class="img-fluid theme-dark" src="/assets/images/elsalam/0J6A1786.jpg" alt="brand-logo" />
                </div>
            </SwiperSlide>

            <SwiperSlide>
                <div class="brand-logo">
                    <img class="img-fluid theme-light" src="/assets/images/elsalam/0J6A1996.jpg" alt="brand-logo" />
                    <img class="img-fluid theme-dark" src="/assets/images/elsalam/0J6A1996.jpg" alt="brand-logo" />
                </div>
            </SwiperSlide>

            <SwiperSlide>
                <div class="brand-logo">
                    <img class="img-fluid theme-light" src="/assets/images/elsalam/0J6A2023.jpg" alt="brand-logo" />
                    <img class="img-fluid theme-dark" src="/assets/images/elsalam/0J6A2023.jpg" alt="brand-logo" />
                </div>
            </SwiperSlide>

            <SwiperSlide>
                <div class="brand-logo">
                    <img class="img-fluid theme-light" src="/assets/images/elsalam/0J6A2034.jpg" alt="brand-logo" />
                    <img class="img-fluid theme-dark" src="/assets/images/elsalam/0J6A2034.jpg" alt="brand-logo" />
                </div>
            </SwiperSlide>

            <SwiperSlide>
                <div class="brand-logo">
                    <img class="img-fluid theme-light" src="/assets/images/elsalam/0J6A2148.jpg" alt="brand-logo" />
                    <img class="img-fluid theme-dark" src="/assets/images/elsalam/0J6A2148.jpg" alt="brand-logo" />
                </div>
            </SwiperSlide>

           
        </Swiper>
    </div>
</template>
