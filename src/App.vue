<script setup>
import "@esri/calcite-components/dist/components/calcite-shell";
import "@esri/calcite-components/dist/components/calcite-navigation";
import "@esri/calcite-components/dist/components/calcite-navigation-logo";

import Map from "./components/Map.vue";

</script>

<template>
  <calcite-shell>
    <calcite-navigation slot="header">
      <calcite-navigation-logo
        slot="logo"
        icon="script"
        heading="ArcGIS / Vue Template"
      ></calcite-navigation-logo>
    </calcite-navigation>
    <Map />
  </calcite-shell>

</template>

<style>

</style>
