<template>
  <footer class="footer">
    <div class="col-1">
      <h3>SNEAK.</h3>
    </div>
    <div class="col-2">
      <h3>SOBRE SNEAK.</h3>
      <p>Novidades</p>
      <p>Carreira</p>
      <p>Para investidores</p>
      <p>Cuidado com o meio ambiente</p>
    </div>
    <div class="col-3">
      <h3>AJUDA</h3>
      <p>Status do pedido</p>
      <p>Entregas e frete</p>
      <p>Trocas e devoluções</p>
      <p>Opções de pagamentos</p>
    </div>
    <div class="col-4">
      <h3>REDES SOCIAIS</h3>
      <img src="../assets/instagram.svg">
      <img src="../assets/x.svg">
      <img src="../assets/facebook.svg">
    </div>
  </footer>
  <div class="designer">
    <h2>Desenvolvido por <b><a href="#">Habbiner</a>  </b></h2>
  </div>
</template>

<script>
  export default {

  }
</script>

<style scoped>

  footer {
    background-color: #F3F3F3;
    margin-top: 100px;
    width: 100%;
    display: flex;
    justify-content: center;
    padding-bottom: 50px;
  }

  h3, p {
    font-size: 20px;
  }

  .col-1 {
    width: 365px;
  }

  .col-2 {
    width: 365px;
  }

  .col-3 {
    width: 365px;
  }

  .col-4 {
    width: 365px;
  }

  .col-4 img {
    margin-right: 20px;
  }

  .designer {
    display: flex;
    justify-content: center;
    background-color: #F3F3F3;
  }

  .designer a, h2 {
    font-size: 20px;
    text-decoration: none;
    color: black;
  }

</style>