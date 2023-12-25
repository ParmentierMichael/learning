<template>
  <div>
    <!-- Boutons & variants -->
    <v-btn> Cliquez </v-btn>
    <v-btn variant="outlined"> Cliquez </v-btn>
    <v-btn variant="tonal"> Cliquez </v-btn>
    <v-btn variant="text"> Cliquez </v-btn>
    <v-btn variant="plain"> Cliquez </v-btn>
    <v-btn variant="elevated"> Cliquez </v-btn>
    <v-btn variant="flat"> Cliquez </v-btn>

    <!-- Affiche une icone  -->
    <v-btn icon="$vuetify"></v-btn>
    <!-- Icone + label -->
    <v-btn prepend-icon="$vuetify"> Cliquez </v-btn>
    <!-- Label + Icone -->
    <v-btn append-icon="$vuetify"> Cliquez </v-btn>
    <!-- Icone + label + icone -->
    <v-btn prepend-icon="$vuetify" append-icon="$vuetify"> Cliquez </v-btn>
    <!-- Pile -->
    <v-btn stacked prepend-icon="$vuetify" append-icon="$vuetify">
      Cliquez
    </v-btn>
  </div>
</template>

<script setup></script>
