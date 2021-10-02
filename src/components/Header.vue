<template>
  <header>
      <h1>cioa</h1>
      <Info/>
      <Title/>
  </header>
</template>

<script>
import Info from './Info.vue';
import Title from './Title.vue';
export default {
    name: "Header",
    components:{
        Info,
        Title,
    }
}
</script>

<style scoped lang="scss">

</style>