<template>
  <h2 class="text-3xl font-bold mb-4 text-center">Intip Video Proses Sablon</h2>
    <div class="w-full p-4 flex justify-center">
      <iframe
        width="360"
        height="560"
        :src="videoSrc"
        frameborder="0"
        allow="autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture "
        allowfullscreen
        class="h-calc[80vh] object-cover object-center rounded-md"
      ></iframe>
    </div>
  </template>
  
  <script>
  export default {
    name: 'YouTubeShorts',
    data() {
      return {
        // Gantilah ini dengan ID video Shorts Anda
        videoId: 'KGsSU1iEYaA', // Ganti dengan ID video Shorts yang sesuai
      };
    },
    computed: {
      videoSrc() {
        return `https://www.youtube.com/embed/${this.videoId}`;
      },
    },
  };
  </script>
  
  <style scoped>
  
  </style>