<template>
  <v-col align="center">
    <v-card
      to="/orders"
      class="ma-3 pt-1 elevation-5 orange lighten-5 fade"
      width="50%"
    >
      <v-list-item three-line>
        <v-list-item-avatar
          size="80"
          color="orange lighten-2"
          class="elevation-10"
        >
          <v-icon large> mdi-clipboard-check</v-icon>
        </v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="headline mb-1">
            <span>Sprawdź zamówienia</span>
          </v-list-item-title>
          <v-list-item-subtitle>
            <span>Edytuj statusy zamowien</span>
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
    </v-card>

    <v-card
      to="/orders/current"
      class="ma-3 pt-1 elevation-5 orange lighten-5 fade"
      width="50%"
    >
      <v-list-item three-line>
        <v-list-item-avatar
          size="80"
          color="orange lighten-2"
          class="elevation-10"
        >
          <v-icon large> mdi-clipboard-arrow-left</v-icon>
        </v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="headline mb-1">
            <span>Oczekujące zamowienia</span>
          </v-list-item-title>
          <v-list-item-subtitle
            >Zamówienia czekające na obsługę</v-list-item-subtitle
          >
        </v-list-item-content>
      </v-list-item>
    </v-card>
  </v-col>
</template>

<script>
export default {
  name: "MainBarmanPage"
};
</script>
<style scoped>
.fade:hover {
  opacity: 0.5;
}
</style>
