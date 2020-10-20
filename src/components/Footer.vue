<template>
  <v-footer light padless>
    <v-card class="flex" flat tile>
      <v-card-title class="teal">
        <div class="a">
          Contáctenos | Términos de Uso | Privacidad | Cookies | Seguridad
        </div>

        <v-spacer></v-spacer>

        <v-btn v-for="icon in icons" :key="icon" class="mx-4" icon>
          <v-icon size="24px">{{ icon }}</v-icon>
        </v-btn>
      </v-card-title>

      <v-divider></v-divider>

      <v-card-text class="b"> © 2018 CLIENTE. All Rights Reserved </v-card-text>
    </v-card>
  </v-footer>
</template>

<style scoped>
div {
  color: #797979;
}

.a {
  height: 17px;

  color: #797979;

  font-family: Montserrat;

  font-size: 12px;

  font-weight: 400;

  font-style: normal;

  letter-spacing: normal;

  line-height: normal;

  text-align: left;
}

.b {
  height: 15px;

  color: #797979;

  font-family: Arial;

  font-size: 12px;

  font-style: normal;

  letter-spacing: normal;

  line-height: normal;

  text-align: left;
}
</style>

<script>
export default {
  data: () => ({
    icons: ["mdi-facebook", "mdi-youtube", "mdi-instagram"],
  }),
};
</script>