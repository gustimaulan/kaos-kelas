<template>
    <section id="order" class="my-12 px-4">
      <h2 class="text-3xl font-bold text-center">Cara Pemesanan Kaos Kelas</h2>
      <ol class="list-decimal list-inside mt-4">
        <li>Menghubungi kami melalui WA</li>
        <li>Konsultasi mengenai desain atau memiliki desain sendiri</li>
        <li>Konfirmasi pesanan dan lakukan pembayaran muka</li>
        <li>Kaos masuk proses printing</li>
      </ol>
      <div class="flex flex-col justify-center mt-4 items-center">
        <img src="/images/panah-gif.gif" alt="arah panah">
        <WhatsAppButton class=" w-full mx-auto mt-8 py-4 px-8" />
      </div>
    </section>
  </template>
  
  <script>
  import WhatsAppButton from './WhatsAppButton.vue';
  export default {
    name: 'OrderingProcess',
    components: {
      WhatsAppButton,
    },
  }
  </script>