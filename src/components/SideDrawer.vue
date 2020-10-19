<template>
  <v-navigation-drawer
    v-model="drawer"
    :mini-variant.sync="mini"
    absolute
    permanent
    left
    id="draw"
  >
    <v-btn icon @click.stop="mini = !mini">
      <v-icon>mdi-chevron-right</v-icon>
    </v-btn>
    <v-divider></v-divider>

    <v-list dense>
      <v-list-item>
        <img src="../assets/draw-1.png" />
        <v-list-item-title>Perfil</v-list-item-title>
      </v-list-item>
      <v-list-item>
        <img src="../assets/draw-2.png" />
        <v-list-item-title>Finanzas</v-list-item-title>
      </v-list-item>
      <v-list-item>
        <img src="../assets/draw-3.png" />
        <v-list-item-title>Ajustes</v-list-item-title>
      </v-list-item>
      <v-list-item>
        <img src="../assets/draw-4.png" />
        <v-list-item-title>Proyecciones</v-list-item-title>
      </v-list-item>
    </v-list>
  </v-navigation-drawer>
</template>

<script>
export default {
  data() {
    return {
      drawer: false,
      mini: true,
    };
  },
};
</script>