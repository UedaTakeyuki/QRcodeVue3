<template>
<v-app>
  <QR/>
  <v-main>
  </v-main>
</v-app>
</template>

<script>
import QR from 'qrcode-of-this-site'
export default {
  components: {QR},
}
</script>