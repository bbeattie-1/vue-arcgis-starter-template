<script setup>

import "@arcgis/map-components/dist/components/arcgis-map";

</script>

<template>

    <arcgis-map basemap="satellite" zoom="8" center="-92,40"></arcgis-map>

</template>

<style scoped>

arcgis-map {
    width: 100%;
    height: 100%;
}

</style>