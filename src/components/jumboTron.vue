<template>
    <div class="jumbo">
        <img src="../assets/puntaCampanella.jpg" alt="">
        <div class="fig">
        <h2>Questo è il Jumbotron di un sito fatto male <br> ma con una bella foto!</h2>
        </div>
    </div>
</template>

<script>
export default{
    name:'jumboTron'
}
</script>
<style scoped>
   .jumbo{
    position: relative;
   } 
  img{
      width: 100vw;
      opacity: 0.6;
      filter: sepia(60%);
  }
  .fig{
      position: absolute;
      top: 50%;
     left: 50%;
     transform: translate(-50%, -50%);
  }
</style>
