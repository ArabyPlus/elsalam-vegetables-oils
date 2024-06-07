<template>
  <section class="contact mb-10">

    <ContactInfo :info="contactData" />
    <div class="container-fluid">
      <div class="row">
        <ContactMap :map="contactData.map" />
        <div class="col-lg-6 form">
          <div class="mx-auto text-center mb-10">
            <h1 class="mb-4 text-4xl font-bold">اتصل بنا</h1>
            <h1>كن على تواصل معنا</h1>
          </div>
          <div class="flex flex-col justify-center items-center gap-4">
<input type="text" placeholder="الإسم" class="text-center rounded py-2 px-10 w-100" style="border: 1px solid;">
<input type="text" placeholder="الإيميل" class="text-center rounded py-2 px-10 w-100" style="border: 1px solid;">
<textarea name="الرسالة" placeholder="الرسالة" cols="30" rows="10" class="text-center rounded py-2 px-10 w-100" style="border: 1px solid;"></textarea>
<button class="bg-green-500 py-2 px-16 text-xl font-bold rounded text-center text-white hover:bg-green-700">إرسال</button>

          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import ContactInfo from './Info.vue';
import ContactMap from './Map.vue';
import ContactForm from './Form.vue';
//= Static Data
import contactData from "/data/contact.json";
</script>
