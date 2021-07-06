<template>
  <div class="hello">
   
   <!-- <p class="seskater"> some viewers may find the content linked below inapropreate. please click "accept terms" to be able to wiev... </p>  
  <iframe v-if="deth === true" id="ytplayer" type="text/html" width="1000" height="500"
  src="https://www.youtube.com/embed/dQw4w9WgXcQ?autoplay=1&origin=http://example.com"
  frameborder="0"/> -->
  <!-- <iframe v-if="deth === true" width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" autoplay:1 title="YouTube video player" frameborder="0" allow="accelerometer; autoplay:1 ; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
    <v-btn
      class="ma-2"
      :loading="loading"
      :disabled="loading"
      color="secondary"
      @click='die'
    >
     show more
    </v-btn>
    <div>
      <v-card
  elevation="21"
  shaped
></v-card>
    </div>
  </div>
</template>

<script>
export default {
  name: 'seskater',
  props: {
    msg: String
  },
   data: function () {
     return {
       deth: false,
    
     }
  },
  methods:{
    die(){
     this.deth= true
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 .seskater {
  display: flex;
  margin: 0 10px;
}

</style>
