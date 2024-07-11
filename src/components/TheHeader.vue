<template>
  <div class="container">
    <header class="header">
      <div class="bloco1">
        <span>SNEAK.</span>
      </div>
      <div class="options bloco2">
        <span>Masculino</span>
        <span>Feminino</span>
        <span>Novidades</span>
        <span>Ofertas</span>
        <span>Coleções</span>
      </div>
      <div class="procurar-sacola bloco3">
        <input type="text" placeholder="Procurar">
        <img src="../assets/sacola.svg">
      </div>
    </header>
  </div>
</template>

<script>
  export default {

  }
</script>

<style>

  .container {
    display: flex;
    justify-content: center;
    flex-direction: column;
  }

  .header {
    height: 92px;
    width: 1600px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    position: relative;
  }

  span:hover {
    cursor: pointer;
    transform: translateX(0px) translateY(-5px);
    transition-duration: 0.5s;
    box-shadow: 0px 2px 0px 0px rgba(0, 0, 0, 0.2);
  }

  .bloco1 {
    width: 30%;
    color: #42b983;
  }

  .bloco2 {
    width: 40%;
    color: pink;
  }

  .bloco3 {
    width: 35%;
    color: beige;
    justify-content: flex-end;
  }

  .options {
    display: flex;
    justify-content: space-between;
  }

  span {
    color: black;
    margin-left: 34px;
    font-size: 20px;
  }

  input[type=text] {
    width: 235px;
    height: 52px;
    border-radius: 50px;
    margin-right: 24px;
    padding-left: 28px;
  }

  .procurar-sacola {
    display: flex;
    margin-right: 72px;
  }

</style>