<template>
  <div class="info pt-80 pb-80 text-center">
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <div class="item">
            <Icon name="material-symbols:call" class="text-3xl" />
            <div class="cont">
              <h6 class="custom-font">تواصل معنا</h6>
              <p>20-45-3281162</p>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="item">
            <Icon name="material-symbols:attach-email" class="text-3xl" />
            <div class="cont">
              <h6 class="custom-font">التواصل عبر البريد الإلكتروني</h6>
              <p>info@elsalamoil.com</p>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="item">
            <Icon name="material-symbols:location-on" class="text-3xl" />
            <div class="cont">
              <h6 class="custom-font">العنوان</h6>
              <p> الكيلو 57 طريق الاسكندريه القاهرة الزراعى دمنهور بعد مجمع الكليات دمنهور ب 200
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const { info } = defineProps(["info"]);
</script>
