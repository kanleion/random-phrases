<template>
  <section class="random-phrase__container">
    <p>Esta sería una nueva Prueba</p>
    <button>Quiero una nueva frase</button>
  </section>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.random-phrase__container{
  display: flex;
  flex-direction: column;
  align-content: center;
  justify-content: center;
  width: 100%;
  height:500px;
}

.random-phrase__container p{
  font-size: 2.8rem;
  font-weight: 400;
  font-family: 'Courier New', Courier, monospace;
}

.random-phrase__container button{
  width: 200px;
  border-radius:25px;
  padding: 10px;
  align-self: center;
}
</style>
