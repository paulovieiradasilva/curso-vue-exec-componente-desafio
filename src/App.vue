<template>
  <v-app>
    <app-menu />
    <app-toolbar />
    <v-content>
      <app-carrousel />
    </v-content>
    <app-footer />
  </v-app>
</template>

<script>
import Footer from "./Footer.vue";
import Carrousel from "./Carrousel.vue";
import Toolbar from "./Toolbar.vue";
import Menu from "./Menu.vue";

export default {
  components: {
    "app-menu": Menu,
    "app-carrousel": Carrousel,
    "app-toolbar": Toolbar,
    "app-footer": Footer,
  },
};
</script>
