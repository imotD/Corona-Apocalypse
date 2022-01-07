<template>
  <v-app-bar color="transparent" flat dark>
    <v-toolbar-title>
      <v-avatar tile>
        <img src="@/assets/img/icon.png" alt="logo" />
      </v-avatar>
    </v-toolbar-title>

    <v-spacer></v-spacer>

    <v-btn icon>
      <v-icon>mdi-apps </v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name: 'NavItem',
}
</script>

<style lang="scss" scoped></style>
