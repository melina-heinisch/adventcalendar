<template>
<v-card :class="backgroundNr" class="fenster ma-3" @click="clicked = !clicked">
  <v-card-text class="number" v-if="!clicked">{{number}}</v-card-text>
  <v-card-text class="text" v-if="clicked">{{text}}</v-card-text>
</v-card>
</template>

<script>
export default {
  name: "Fenster",
  data: () => ({
    clicked: false

  }),
  props: {
    number: {
      type: String,
      required: true
    },
    text: {
      type: String,
      required: true
    },
    backgroundNr: {
      type: String,
      required: true
}
  },

  computed:{
  }
}


</script>

<style scoped>

.fenster{
  width: 250px;
  height: 250px;

}

.number{
  font-size: 128px;
  text-align: center;
  margin-top: 100px;
}

.text{
  font-size: 20px;
  color: black !important;
}

.one{
  background: url(../assets/1.jpg);

}
.two{
  background: url(../assets/2.jpg) ;

}
.three{
  background: url(../assets/3.jpg) ;

}
.four{
  background: url(../assets/4.jpg) ;

}

</style>