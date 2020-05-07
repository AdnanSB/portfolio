<template>
  <v-app class="indigo lighten-1">
    <NavBar />
    <v-content>
      <router-view />
      <router-link to="/Projects"></router-link>
      <router-link to="/Home"></router-link>
    </v-content>
  </v-app>
</template>

<script>
import NavBar from "@/components/NavBar";

export default {
  name: "App",
  components: { NavBar },
  data: () => ({
    //
  }),
};
</script>
<style lang="scss"></style>
