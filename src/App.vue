<style>

@import url('https://fonts.googleapis.com/css2?family=Sacramento&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Charmonman:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');

  .v-application{
    background: #ecced3!important;
  }
  .v-application .display-1, .v-application .display-2 {
    font-family: Sacramento !important;
  }
  .theme--light.v-application{
    color: rgb(75 36 36 / 87%) !important;
  }
  .v-application .display-1 {
    font-size: 4rem!important;
    line-height : 5rem
  }
  .v-application .display-2 {
    font-size: 5rem!important;
    line-height : 6rem;
    color: rgb(77, 8, 8);
  }
  .v-application .display-3 {
    font-family: Sacramento !important;
    font-size: 4rem!important;
    line-height : 4.25rem;
  }
  .v-application .headline{
    font-family: 'Charmonman', cursive !important;
    font-weight: 700;
    font-size: 1.5rem!important;
    line-height : 2rem;
  }
  .v-application .subheading{
    font-family: 'Lato', sans-serif !important;
  }
  .v-card__title {
    background:floralwhite;
  }
  .v-application .body-2 {
    /* font-family: 'Charmonman', cursive !important;
    font-weight: 700; */
    font-size: 1.1rem!important;
    letter-spacing: .0178571429em!important;
    line-height: 1.25rem;
}
  .v-application .body-2 {
    /* font-family: 'Charmonman', cursive !important;
    font-weight: 700; */
    margin: 1em;
    font-size: 1.1rem!important;
    letter-spacing: .0178571429em!important;
    line-height: 1.4rem;
  }
  .soumyasis{
    margin: 1.5em;
    text-align: left!important;
    font-size: 1.1rem!important;
    letter-spacing: .0178571429em!important;
    line-height: 1.4rem;
  }
</style>

<template>
  <v-app>
    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
</script>
