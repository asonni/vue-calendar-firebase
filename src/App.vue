<template>
  <v-app>
    <v-content>
      <Calander />
    </v-content>
  </v-app>
</template>

<script>
import Calander from "./components/Calander";

export default {
  name: "App",
  components: {
    Calander
  },
  data: () => ({
    //
  })
};
</script>
