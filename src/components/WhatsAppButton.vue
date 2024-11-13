<template>
    <button
      @click="handleWhatsAppClick"
      class="bg-green-600 hover:bg-green-700 text-white font-bold py-2 px-4 rounded"
    >
      Chat ke WhatsApp
    </button>
  </template>
  
  <script>
  export default {
    name: 'WhatsAppButton',
    props: {
      message: {
        type: String,
        default: 'Halo Kak Admin atlasprinting_, Saya mau tanya seputar kaos sablon..',
      },
      phoneNumber: {
        type: String,
        default: '6285161323400',
        required: true,
      },
    },
    methods: {
      handleWhatsAppClick() {
        // Define the message to send
        const encodedMessage = encodeURIComponent(this.message);
        const whatsappLink = `whatsapp://send?phone=${this.phoneNumber}&text=${encodedMessage}`;
  
        // Open the WhatsApp link
        window.open(whatsappLink, '_blank');
  
        // Track the Add to Cart event
        fbq('track', 'AddToCart');
      },
    },
  };
  </script>
  
  <style scoped>
  /* Optional: Add custom styles if needed */
  </style>