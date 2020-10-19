<template>
  <div>
    <TopNav />
    <div class="d-none d-lg-block"><SideDrawer /></div>
    <NombreClienteNav />
    <MainNav />
    <div>
      <h3>Consulta Cliente Domicilio</h3>
    </div>
    <TablaFull />
    <Footer />
  </div>
</template>

<script>
import TablaFull from "./components/TablaFull";
import NombreClienteNav from "./components/NombreClienteNav";
import MainNav from "./components/MainNav";
import Footer from "./components/Footer";
import TopNav from "./components/TopNav";
import SideDrawer from "./components/SideDrawer";

export default {
  name: "App",

  components: {
    NombreClienteNav,
    TablaFull,
    MainNav,
    Footer,
    TopNav,
    SideDrawer,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
h3 {
  margin: 3% 20mm;
}
</style>