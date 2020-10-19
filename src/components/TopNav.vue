<template>
  <div>
    <v-app-bar flat id="top">
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title id="title"
        >Cartera > Clientes > Nombre Cliente</v-toolbar-title
      >

      <v-spacer></v-spacer>

      <v-btn icon>
        <img src="../assets/_Check.png" />
      </v-btn>

      <v-divider vertical></v-divider>

      <v-btn icon>
        <img src="../assets/Fill_1.png" />
      </v-btn>
      <v-divider vertical></v-divider>

      <v-btn icon>
        <img src="../assets/_Buscar_Copy.png" />
      </v-btn>
      <v-divider vertical></v-divider>

      <v-btn icon>
        <img src="../assets/_History.png" />
      </v-btn>
      <v-divider vertical></v-divider>

      <v-btn icon>
        <img src="../assets/_Buscar.png" />
      </v-btn>
      <v-divider vertical></v-divider>

      <v-btn icon>
        <img src="../assets/_Notification.png" />
      </v-btn>
      <v-divider vertical></v-divider>

      <v-btn icon>
        <img src="../assets/User_Avatar.png" />
      </v-btn>
    </v-app-bar>
  </div>
</template>

<style scoped>
#top {
  background-color: white;
}
#title {
  background-color: #f4f6fa;
  border: 1px solid #f4f6fa;
  padding: 9px;
  border-radius: 12px;
  width: 210px;
  height: 30px;
  color: #273f70;
  font-size: 12px;
  font-weight: 400;
  font-style: normal;
  letter-spacing: normal;
  line-height: normal;
  text-align: left;
}
</style>