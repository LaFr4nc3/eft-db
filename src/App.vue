<template>
  <v-app>
    <v-content>
      <v-container>
        <Ammunition></Ammunition>
      </v-container>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Ammunition from "@/components/Ammunition.vue";

@Component({
  components: {
    Ammunition
  }
})
export default class App extends Vue {
  name = "App";
}
</script>
