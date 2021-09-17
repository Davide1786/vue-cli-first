<template>
  <div>
    <h1>La mia prima app con Vue CLI!</h1>
    <img alt="insigne" src="https://cdn.areanapoli.it/immagini/notizie/big/i/insigne_261.jpg">
    <div>
      <h1>Il vecchio Capitano!</h1>
      <img alt="hamsik" src="https://www.gonfialarete.com/wp-content/uploads/2018/12/GettyImages-1066205300-e1549437730242.jpg">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Galleria',
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
</style>
