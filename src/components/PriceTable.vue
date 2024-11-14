<template>
    <div class="my-12 px-4">
      <h2 class="text-3xl font-bold text-center mb-8">Harga Sablon Kaos Kelas</h2>
      <div class="overflow-x-auto">
        <table class="min-w-full bg-white border border-gray-300">
          <thead>
            <tr class="bg-black text-white">
              <th class="py-2 px-4 border">Ukuran Cetak</th>
              <th class="py-2 px-4 border">Harga</th>
              <th class="py-2 px-4 border">Keterangan</th>
            </tr>
          </thead>
          <tbody>
            <tr class="bg-gray-50">
              <td class="py-2 px-4 border">A4</td>
              <td class="py-2 px-4 border">Rp 75.000 / pcs</td>
              <td class="py-2 px-4 border">Kaos Premium</td>
            </tr>
            <tr class="bg-gray-50">
              <td class="py-2 px-4 border">A3</td>
              <td class="py-2 px-4 border">Rp 85.000 / pcs</td>
              <td class="py-2 px-4 border">Kaos Premium</td>
            </tr>
          </tbody>
        </table>
        <p class="p-4 bg-orange-50 text-red-500 font-bold">Info: <span class="font-normal">Harga dapat bertambah tergantung penambahan sablon</span></p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'PriceTable',
  }
  </script>
  
  <style scoped>
  /* Gaya tambahan jika diperlukan */
  </style>