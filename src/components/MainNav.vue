<template>
  <div>
    <v-toolbar>
      <v-slide-group multiple show-arrows>
        <v-slide-item v-slot:default="{ toggle }">
          <v-btn
            class="mx-2"
            active-class="purple white--text"
            depressed
            rounded
            @click="toggle"
          >
            Cliente Generales
          </v-btn>
        </v-slide-item>
        <v-slide-item v-slot:default="{ toggle }">
          <v-btn
            class="mx-2"
            active-class="purple white--text "
            depressed
            rounded
            @click="toggle"
          >
            Cliente Domicilio
          </v-btn>
        </v-slide-item>
        <v-slide-item v-slot:default="{ toggle }">
          <v-btn
            class="mx-2"
            active-class="purple white--text"
            depressed
            rounded
            @click="toggle"
          >
            Cliente Contacto
          </v-btn>
        </v-slide-item>
        <v-slide-item v-slot:default="{ toggle }">
          <v-btn
            class="mx-2"
            active-class="purple white--text"
            depressed
            rounded
            @click="toggle"
          >
            Cliente Equipo
          </v-btn>
        </v-slide-item>
        <v-slide-item v-slot:default="{ toggle }">
          <v-btn
            class="mx-2"
            active-class="purple white--text"
            depressed
            rounded
            @click="toggle"
          >
            Cliente Pólizas
          </v-btn>
        </v-slide-item>
        <v-slide-item v-slot:default="{ toggle }">
          <v-btn
            class="mx-2"
            active-class="purple white--text"
            depressed
            rounded
            @click="toggle"
          >
            Tickets y Documentos
          </v-btn>
        </v-slide-item>
        <v-slide-item v-slot:default="{ toggle }">
          <v-btn
            class="mx-2"
            active-class="purple white--text"
            depressed
            rounded
            @click="toggle"
          >
            Producción
          </v-btn>
        </v-slide-item>
        <v-slide-item v-slot:default="{ toggle }">
          <v-btn
            class="mx-2"
            active-class="purple white--text"
            depressed
            rounded
            @click="toggle"
          >
            Anexos
          </v-btn>
        </v-slide-item>
        <v-slide-item v-slot:default="{ toggle }">
          <v-btn
            class="mx-2"
            active-class="purple white--text"
            depressed
            rounded
            @click="toggle"
          >
            Vistas
          </v-btn>
        </v-slide-item>
      </v-slide-group>
    </v-toolbar>
  </div>
</template>

<style >
.nav .nav-active {
  color: #3c8bfb !important;
  border-bottom: 4px solid #3c8bfb;
  padding-bottom: 0 !important;
}

.theme--light.v-btn:not(.v-btn--flat):not(.v-btn--text):not(.v-btn--outlined).nav {
  background-color: #fff !important;
}

.v-btn--rounded {
  border-radius: 0 !important;
  background-color: #fff !important;
  color: #273f70 !important;
}

button.mx-2:nth-child(2) {
  color: #3c8bfb !important;
  border-bottom: 4px solid #3c8bfb !important;
}
.v-item-group {
  height: 100%;
}
.v-btn:not(.v-btn--round).v-size--default {
  height: 100% !important;
}
body
  > div:nth-child(2)
  > div:nth-child(4)
  > header:nth-child(1)
  > div:nth-child(1) {
  margin: 0 10mm;
}
</style>

