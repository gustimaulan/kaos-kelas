<template>
    <div class="my-12 px-4">
      <h2 class="text-3xl font-bold text-center mb-8">List Harga Sablon Kaos Kelas</h2>
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
              <td class="py-2 px-4 border">Rp 65.000 / pcs</td>
              <td class="py-2 px-4 border">Kaos premium</td>
            </tr>
            <tr class="bg-gray-50">
              <td class="py-2 px-4 border">A3</td>
              <td class="py-2 px-4 border">Rp 70.000 / pcs</td>
              <td class="py-2 px-4 border">Kaos premium</td>
            </tr>
          </tbody>
        </table>
        <p class="p-2 bg-orange-50 text-sm italic"><span class="font-normal">*Kaos lengan Panjang +Rp 5.000</span></p>
        <p class="p-2 bg-orange-50 text-sm italic"><span class="font-normal">**Harga dapat berubah sewaktu-waktu</span></p>
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