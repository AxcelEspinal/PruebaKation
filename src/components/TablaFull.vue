<template>
  <v-card>
    <v-card-title>
      <b>Buscar:</b>
      <v-text-field
        v-model="search"
        append-icon="mdi-magnify"
        label="Escribe lo que deseas buscar..."
        single-line
        hide-details
      ></v-text-field>
      <v-btn depressed color="primary">+ Nuevo Domicilio</v-btn>
    </v-card-title>
    <v-data-table
      :headers="headers"
      :items="clientes"
      :search="search"
    ></v-data-table>
  </v-card>
</template>

<script>
export default {
  data() {
    return {
      search: "",
      headers: [
        {
          text: "...",
          align: "start",
          filterable: false,
          value: "marker",
        },
        { text: "PERSONA NO.", value: "personaNo" },
        { text: "TIPO DOMICILIO", value: "tipoDomicilio" },
        { text: "CALLE", value: "calle" },
        { text: "NÚMERO", value: "numero" },
        { text: "SECTOR", value: "sector" },
        { text: "PROVINCIA", value: "provincia" },
        { text: "ESTADO", value: "estado" },
      ],
      clientes: [
        {
          marker: "...",
          personaNo: 306,
          tipoDomicilio: "Sucursal",
          calle: "Paseo Oeste",
          numero: 4,
          sector: "La Rosaelda",
          provincia: "Santiago",
          estado: "Activo",
        },
        {
          marker: "...",
          personaNo: 306,
          tipoDomicilio: "Residencia",
          calle: "Paseo Oeste",
          numero: 4,
          sector: "La Rosaelda",
          provincia: "Santiago",
          estado: "Activo",
        },
        {
          marker: "...",
          personaNo: 306,
          tipoDomicilio: "Veraneo",
          calle: "Paseo Oeste",
          numero: 4,
          sector: "La Rosaelda",
          provincia: "Santiago",
          estado: "Activo",
        },
      ],
    };
  },
};
</script>

<style >
body {
  font-family: "Roboto";
}
.v-card {
  margin: 3%;
}
.v-data-table-header {
  background-color: #273f70;
}
.text-start span {
  color: #ffffff !important;
}

.v-card__title {
  width: 100%;
  min-width: 315.33px;
}
div.v-input:nth-child(2) > div:nth-child(1) > div:nth-child(1) {
  border-radius: 6px;
  border: 1px solid #dfdfdf;
  padding-left: 10px;
  width: 30%;
  min-width: 292px;
}

.primary {
  background-color: #273f70 !important;
}
div.v-input:nth-child(2) {
  padding-top: 0px;
  margin-top: 0px;
  margin-left: 4px;
  margin-right: 4px;
}

.v-data-footer__select {
  display: none !important;
}
.primary > span:nth-child(1) {
  height: 36px !important;
}

.v-label--active,
.v-data-table-header-mobile__wrapper
  > div:nth-child(1)
  > div:nth-child(1)
  > div:nth-child(1)
  > div:nth-child(1)
  > label:nth-child(1) {
  color: #fff !important;
}

div.v-input:nth-child(2) > div:nth-child(1) > div:nth-child(1)::after,
div.v-input:nth-child(2) > div:nth-child(1) > div:nth-child(1)::before {
  display: none;
}
</style>