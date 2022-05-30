<template>
  <v-card
    :loading="loading"
    class="mx-auto my-12"
    max-width="374"
  >

    <v-img
      max-height="150"
      :src="require('../img/BG-badge-grey.svg')" alt="">
        <Badge></Badge>  
    </v-img>

    <Progress></Progress>

    <v-card-title>Leeractiviteiten</v-card-title>

    <v-card-text>
      <v-row
        align="center"
        class="mx-0"
      >

        <div class="grey--text ms-4">
          4.5 (413)
        </div>
      </v-row>

      <div class="my-4 text-subtitle-1">
        $ • Italian, Cafe
      </div>

      <div>Small plates, salads & sandwiches - an intimate setting with 12 indoor seats plus patio seating.</div>
    </v-card-text>

    <v-divider class="mx-4"></v-divider>

    <v-card-title>Tonight's availability</v-card-title>

    <v-card-text>
        update 22-01-2021
    </v-card-text>

  </v-card>
</template>


<style>

</style>