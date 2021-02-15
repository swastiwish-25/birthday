<template>
  <v-container grid-list-xl>
    <v-layout text-center row wrap>
      <v-flex md12>
        <v-img :src="require('../assets/front.jpg')" contain dark height="600" ></v-img>
      </v-flex>

      <v-flex mb-4>
        <h1 class="display-2">Happy 25th Birthday!</h1>
        <h2 class="display-1">Swasti</h2>
      </v-flex>

      <v-flex xs12>
        <v-btn to="/memories" color="secondary">Let's rewind a bit with memories</v-btn>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script src="./Main.js">
</script>
