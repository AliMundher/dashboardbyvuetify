<template>
  <nav>
    <!-- Start Header -->
    <v-app-bar flat app>
      <v-app-bar-nav-icon class="grey--text" @click="drawer = !drawer">
      </v-app-bar-nav-icon>
      <v-toolbar-title>
        <span class="text-capitalize grey--text">monther</span>
        <span class="font-weight-bold grey--text moon">moon</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn outlined color="grey">
        <span>signs up</span>
        <v-icon right>exit_to_app</v-icon>
      </v-btn>
    </v-app-bar>
    <!-- End Header -->
    <!-- Start Side bar -->
    <v-navigation-drawer app class="blue-grey lighten-5" v-model="drawer">
      <v-list>
        <v-list-item
          v-for="link in links"
          :key="link.text"
          router
          :to="link.route"
        >
          <v-list-item-action>
            <v-icon>{{ link.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title>{{ link.text }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <!-- End Side bar -->
  </nav>
</template>

<script>
export default {
  name: "Nav",
  data() {
    return {
      drawer: false,
      links: [
        { icon: "dashboard", text: "Dashboard", route: "/" },
        { icon: "folder", text: "Folder", route: "/project" },
        { icon: "persone", text: "Team", route: "/team" },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
nav {
  .moon {
    text-transform: capitalize !important;
  }
}
</style>
