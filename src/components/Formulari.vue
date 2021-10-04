<template>
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <h1>Formulari</h1>
        <form @submit.prevent>
          <div class="form-group">
            <label for="nom">Faciliti el seu nom:</label>
            <span  >Requerit*</span>
            <input type="text" id="nom" class="form-control" placeholder="Sandokan" v-model="nom">
          </div>

          <div class="form-group">
            <label for="mobil">Faciliti el seu numero cel·lular:</label>
            <span>Requerit*</span>
            <input type="tel" id="mobil" class="form-control" placeholder="123 321 098" >
          </div>

          <div class="form-group">
            <label for="postaql">Faciliti el seu codi postal:</label>
            <span>Requerit*</span>
            <input type="text" id="postal" class="form-control" placeholder="12331" >
          </div>

          <div class="form-group">
            <label for="mail">Faciliti el seu correu electrònic:</label>
            <span>Requerit*</span>
            <input type="email" id="mail" class="form-control" placeholder="guaitatu@boina.net" >
          </div>

          <button type="submit">Enviar</button>

          
        </form>
      </div>

    </div>
  </div>
</template>

<script src="./scripts/formulari.js">
/* export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
} */
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="./styles/formulari.css">
/* h3 {
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
} */
</style>
