<template>
  <v-toolbar>
    <v-toolbar-side-icon>
      <img src="../assets/brand.svg" />
    </v-toolbar-side-icon>
    <v-toolbar-title>Nombre Cliente</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn elevation="3" small><img src="../assets/p.png" />Editar</v-btn>
      <v-btn elevation="3" small><img src="../assets/x.svg" /></v-btn>
    </v-toolbar-items>
  </v-toolbar>
</template>


<style>
body {
  font-family: "Roboto";
}
header.v-sheet:nth-child(2) > div:nth-child(1) {
  background-color: #f4f6fa;
}

header.v-sheet:nth-child(3)
  > div:nth-child(1)
  > v-toolbar-side-icon:nth-child(1) {
  margin: 0 0 0 15mm;
}
.v-card {
  margin: 3% 15mm;
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
}

div.v-input:nth-child(2) {
  padding-top: 0px;
  margin-top: 0px;
  margin-left: 4px;
  margin-right: 4px;
}

button.elevation-3:nth-child(1) {
  margin-right: 20px;
  border-radius: 7px;
  height: 75% !important;
  align-self: center;
}
button.elevation-3:nth-child(2) {
  border-radius: 7px;
  height: 75% !important;
  align-self: center;
}

button.elevation-3:nth-child(1) > span:nth-child(1) > img:nth-child(1) {
  height: 15px;
  margin-right: 5px;
}
.v-toolbar__title {
  margin-left: 10px;
}
button.elevation-3:nth-child(1),
button.elevation-3:nth-child(2) {
  background-color: #fff !important;
}
</style>