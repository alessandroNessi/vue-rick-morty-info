<template>
  <main>
      <h1>Cards</h1>
      <Card/>
  </main>
</template>

<script>
import Card from "./Card.vue";
import axios from 'axios';
export default {
    name: 'Cards',
    components:{
        Card,
    },
    created(){
        axios.get("https://rickandmortyapi.com/api/character").then((answer)=>{
            console.log(answer);
        });
    }
}
</script>

<style scoped lang="scss">

</style>