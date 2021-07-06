<template>
  <v-card
    class="mx-auto"
    max-width="344"
    outlined
  >
    <a class=   'sus' href="https://www.youtube.com/watch?v=dQw4w9WgXcQ&feature=emb_logo&ab_channel=RickAstley">
        <v-list-item three-line>
        <v-list-item-content>
            <div class="text-overline mb-4">
            HEllO, {{ user.name }}
            </div>
            <v-list-item-title class="text-h5 mb-1">
            watch now,{{user.name}}
            </v-list-item-title>
            <v-list-item-subtitle>Woman killed with Amongus Plushie </v-list-item-subtitle>
        </v-list-item-content>

        <v-list-item-avatar
            tile
            size="80"
            color="grey"
        >
        <v-img
            height="80"
            src="../../public/amoguss.jpeg"
            ></v-img>
        </v-list-item-avatar>
        </v-list-item>
    </a>
    
  </v-card>
 
</template>

<script>
export default {
  name: 'seskater',
  props: {
    msg: String
  },
   data: function () {
     return {
       title: 'seskater',
       number: 69,
       user: {
         name: 'Seskater',
         link: 'https://youtu.be/dQw4w9WgXcQ',
         sus: 'Y',
         img:'./public/amoguss.jpeg'
       }
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
.sus {
    text-decoration: none;
 }
</style>
