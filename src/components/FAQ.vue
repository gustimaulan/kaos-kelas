<template>
    <div class="my-12 px-4">
      <h2 class="text-3xl font-bold text-center mb-6">Frequently Asked Questions</h2>
      <div>
        <div
          v-for="(item, index) in faqs"
          :key="index"
          class="mb-4 border-b p-4 "
        >
          <div class="bg-gray-100 px-4 py-2"><h3 class="text-lg font-semibold">▶️ {{ item.question }}</h3></div>
          <p class="mt-2 px-4">{{ item.answer }}</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'FAQ',
    data() {
      return {
        faqs: [
          {
            question: 'Berapa lama waktu pengerjaan?',
            answer: '10-14 hari tergantung pada jumlah antrian'
          },
          {
            question: 'Berapa minimum DP untuk pemesanan?',
            answer: 'Minimum DP adalah 60% dari total'
          },
          {
            question: 'Apa benefit sablon kaos di Atlas Printing?',
            answer: 'Dapat free 1 pcs kaos walas + free sticker bebas desain'
          },
          {
            question: 'Apakah pesanan bisa diantar jika sudah jadi?',
            answer: 'Ya, untuk area barlingmasca bisa diantar'
          },
          {
            question: 'Apakah bisa dibuatkan desainnya?',
            answer: 'Ya, dengan catatan ada referensi contoh desain yang diinginkan'
          },
        ],
      };
    },
  };
  </script>
  
  <style scoped>
  
  </style>