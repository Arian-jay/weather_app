<template>
  <v-app>
    <v-main>
      <WeatherTrack/>
    </v-main>
  </v-app>
</template>

<script>
import WeatherTrack from './components/WeatherTrack.vue';


export default {
  name: 'App',

  components: {
    WeatherTrack,
  },

  data: () => ({
    //
  }),
}
</script>
