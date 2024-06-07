<script setup lang="ts">
useHead({
        bodyAttrs: {
            class: "navbar-light"
        },
    })
const more = ref(false);
</script>

<template>
  <section id="faqs-2" class="gr--whitesmoke  inner-page-hero faqs-section division text-center"
  >
    <img class="img-fluid rounded mx-auto mb-6 w-[50%] " src="/assets/images/elsalam/z1.jpg" alt="content-image">
    <div class="container">
      <div class="row  justify-content-center">
        <div class="col-lg-11 col-xl-10">
          <div class="inner-page-title">
            <h2 class="s-52 w-700">
              زيت الزيتون
            </h2>
            <p class="text-xl" style="line-height:2;">
              زيت الزيتون هو زيت يتم استخراجه من ثمار شجرة الزيتون. يعتبر من
              الزيوت الصحية للغاية، حيث يحتوي على نسبة
              عالية من الأحماض الدهنية الأحادية غير المشبعة ومضادات الأكسدة. يُستخدم بشكل واسع في الطهي، السلطات،
              والتتبيلات، ويشتهر بفوائده الصحية للقلب والأوعية الدموية. كما يستخدم زيت الزيتون في مستحضرات التجميل
              والعناية بالبشرة والشعر.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section id="faqs-2" class="gr--whitesmoke  inner-page-hero faqs-section division text-center">
    <img class="img-fluid rounded mx-auto mb-6 w-[50%]" src="/assets/images/elsalam/z2.jpg" alt="content-image">
    <div class="container">
      <div class="row  justify-content-center">
        <div class="col-lg-11 col-xl-10">
          <div class="inner-page-title">
            <h2 class="s-52 w-700">
              زيت بذور الكتان
            </h2>
            <p class="text-xl" style="line-height:2;">
              يُعدّ زيت بذور الكتان غنيًا بأحماض أوميغا 3 الدهنية، والتي تُعزّز صحة القلب والدماغ. كما يُحسّن الهضم
              ويُقلّل من خطر الإصابة بأمراض مزمنة مثل السرطان والتهاب المفاصل. يُمكن إضافته إلى العصائر أو الزبادي، أو
              استخدامه في الطهي أو صلصات السلطات.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <div v-if="more">
    <section id="faqs-2" class="gr--whitesmoke  inner-page-hero faqs-section division text-center">
      <img class="img-fluid rounded mx-auto mb-6 w-[50%] sm:h-100 md:h-[500px]" src="/assets/images/elsalam/z3.jpg"
        alt="content-image">
      <div class="container">
        <div class="row  justify-content-center">
          <div class="col-lg-11 col-xl-10">
            <div class="inner-page-title">
              <h2 class="s-52 w-700">
                زيت جوز الهند
              </h2>
              <p class="text-xl" style="line-height:2;">
                غنيٌّ بالأحماض الدهنية ذات السلسلة المتوسطة، ممّا يُساعد على حرق الدهون وتحسين صحة الأمعاء. كما يُعزّز
                صحة القلب والدماغ ويُحسّن وظائف الإدراك. يُمكن استخدامه في الطهي بأنواعه المختلفة، أو كبديل للزبدة، أو
                في العناية بالبشرة والشعر.

              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="faqs-2" class="gr--whitesmoke  inner-page-hero faqs-section division text-center">
      <img class="img-fluid rounded mx-auto mb-6 w-[50%] sm:h-100 md:h-[500px]" src="/assets/images/elsalam/z4.jpg"
        alt="content-image">
      <div class="container">
        <div class="row  justify-content-center">
          <div class="col-lg-11 col-xl-10">
            <div class="inner-page-title">
              <h2 class="s-52 w-700">
                زيت عباد الشمس
              </h2>
              <p class="text-xl" style="line-height:2;">
                يُعدّ زيت عباد الشمس غنيًا بفيتامين E، مضاد الأكسدة الذي يُحارب الجذور الحرّة ويُحافظ على صحة الخلايا.
                كما يُحسّن صحة القلب والدماغ ويُقلّل من خطر الإصابة بأمراض القلب والسرطان. يُمكن استخدامه في الطهي
                بأنواعه المختلفة، أو كصلصة للسلطات، أو في العناية بالبشرة والشعر.

              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="faqs-2" class="gr--whitesmoke  inner-page-hero faqs-section division text-center">
      <img class="img-fluid rounded mx-auto mb-6 w-[50%] sm:h-100 md:h-[500px]" src="/assets/images/elsalam/z5.jpg"
        alt="content-image">
      <div class="container">
        <div class="row  justify-content-center">
          <div class="col-lg-11 col-xl-10">
            <div class="inner-page-title">
              <h2 class="s-52 w-700">
                زيت فول الصويا
              </h2>
              <p class="text-xl" style="line-height:2;">
                غنيٌّ بفيتامين E والدهون الأحادية غير المشبعة والدهون المتعددة غير المشبعة، ممّا يُعزّز صحة القلب
                والدماغ ويُقلّل من خطر الإصابة بأمراض القلب والسرطان. يُمكن استخدامه في الطهي بأنواعه المختلفة، أو كصلصة
                للسلطات، أو في تحضير المايونيز والصلصات.


              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
  <div class="w-100 text-center mx-auto my-20">
    <button v-if="more" class="bg-green-500 py-2 px-16 text-xl font-bold rounded text-center mx-auto text-white"
      @click="more = !more">
      مشاهدة أقل
    </button>
    <button v-else class="bg-green-500 py-2 px-16 text-xl font-bold rounded text-center mx-auto text-white" @click="more = !more">
      مشاهدة
      المزيد
    </button>
  </div>
</template>
