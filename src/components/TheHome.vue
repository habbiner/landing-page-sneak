<template>
  <div class="container">
    <section class="carrocel">
      <div class="esquerda">
        <h1><b>SNEAK.</b></h1>
        <h1>Ultra Light</h1>
        <p>
          Os tênis SNEAK foram criados especificamente para treinos de circuito, seja para aulas fitness em casa ou para sua própria rotina de treinos.
        </p>
        <button class="addCarrinho">Adicionar ao Carrinho <i class="fa-solid fa-plus"></i></button>
      </div>
      <img src="../assets/tenis-home.svg">
    </section>
    <section class="card-carrocel">
      <h2>CORRIDA - MASCULINO</h2>
      <div class="opcoes-cores">
        <img src="../assets/color1.svg">
        <img src="../assets/color2.svg">
        <img src="../assets/color3.svg">
        <img src="../assets/color4.svg">
      </div>
      <div class="produto-tenis">
        <img src="../assets/tenis-model1.svg">
        <p>Branco</p>
      </div>
      <button>Adicionar ao Carrinho</button>
    </section>
  </div>
  <section class="card-descricao">
      <div class="esquerda">
        <h2>Leveza e agilidade</h2>
        <p>
          A construção ligeira de espuma e malha do SNEAK proporcionam conforto e agilidade durante o exercício.
          Um “burpee break” na parte frontal do pé torna-o extremamente flexível para fazer prancha ou Mountain Climber.
        </p>
      </div>
      <div class="direita">
        <img src="../assets/leveza.svg">
      </div>
  </section>
  <section class="card-descricao">
    <div class="esquerda">
      <img src="../assets/amortecimento.svg">
    </div>
    <div class="direita">
      <h2>Amortecimento <br> imediato</h2>
      <p>
        A espuma grossa sob o pé absorve o impacto e retorna a energia ao correr com os joelhos altos e ao saltar. 
        O suporte de arco da parte média do pé garante conforto durante todo o treino.
      </p>
    </div>
  </section>
  <section class="card-descricao">
    <div class="esquerda">
      <h2>Sensação de estabilização</h2>
      <p>
        O outrigger - a proteção lateral - dá estabilidade ao pé ao fazer movimentos laterais, como por exemplo, o Skater Squat.
      </p>
    </div>
    <div class="direita">
      <img src="../assets/estabilizacao.svg">
    </div>
  </section>
  <section class="corra">
    <h1>
      CORRA <br> COMO SE O MUNDO <br> DEPENDESSE DE VOCÊ
    </h1>
    <img src="../assets/corra.svg">
  </section>
  <section class="card-maps">
    <div class="map-esquerda">
      <img src="../assets/maps.svg">
    </div>
    <div class="map-direita">
      <h3>Entre em contato</h3>
      <input type="text" placeholder="Nome">
      <input type="email" placeholder="Email">
      <textarea placeholder="Comentários"></textarea>
      <div style="display: flex; align-items: center; margin-top: 48px">
        <input type="checkbox" id="check">
        <label for="check">Concordo com a politica de privacidade</label>
      </div>
      <button>Enviar</button>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'TheHome',
  }
</script>

<style>
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100%;
  }

  .carrocel {
    width: 1600px;
    height: 581px;
    display: flex;
    margin-bottom: 40px;
    margin-top: 80px;
  }

  .esquerda h1 {
    background: linear-gradient(to left, #DADADA, #9F9F9F);
    background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  .esquerda button {
    width: 336px;
    height: 84px;
    border-radius: 12px;
    font-size: 20px;
    border: 2px solid;
    margin-top: 10%;
    margin-left: 80px;
    background-color: transparent;
  }

  h1 {
    font-size: 104px;
    margin: 0;
    padding-left: 80px;
  }

  .esquerda p {
    font-size: 20px;
    padding-left: 80px;
  }

  .produto-tenis {
    text-align: center;
  }

  .card-carrocel {
    width: 1600px;
    height: 767px;
    background-color: #F3F3F3;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-top: 5%;
  }

  .opcoes-cores img {
    padding: 20px;
  }

  h2 {
    font-size: 40px;
  }

  .card-carrocel button {
    width: 336px;
    height: 84px;
    border-radius: 12px;
    font-size: 20px;
    border: 2px solid;
    background-color: transparent;
  }

  .card-carrocel p {
    font-size: 20px;
  }

  .card-descricao {
    width: 100%;
    height: 767px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .card-descricao h2 {
    font-size: 64px;
    background: linear-gradient(to left, #DADADA, #9F9F9F);
    background-clip: text;
    -webkit-text-fill-color: transparent;

  }

  .card-descricao p {
    padding-left: 0px;
    margin-right: 155px;
    font-size: 20px;
    width: 580px;
  }

  .card-descricao .direita p {
    margin-left: 155px;
    margin-right: 0px;
  }

  .card-descricao .direita h2 {
    margin-right: 0px;
    margin-left: 155px;
  }

  .corra {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
  }

  .corra h1 {
    position: absolute;
    display: flex;
    color: white;
    font-size: 100px;
    padding: 0px;
  }

  .card-maps {
    display: flex;
    justify-content: center;
    margin-top: 100px;
  }

  .map-direita {
    display: flex;
    flex-direction: column;
    width: 613px;
    padding-left: 20px;
    background-color: #F3F3F3;
  }

  .map-direita h3 {
    font-size: 40px;
  }

  .map-direita input[type=text], input[type=email] {
    width: 517px;
    height: 76px;
    border-radius: 12px;
    border: none;
    margin-bottom: 24px;
    padding-left: 28px;
  }

  textarea {
    width: 517px;
    height: 260px;
    border-radius: 12px;
    padding-left: 28px;
    padding-top: 24px;
    border: none;
  }

  input[type=checkbox] {
    width: 28px;
    height: 28px;
    margin-right: 16px;
    border: none;
  }

  label {
    font-size: 20px;
  }

  .map-direita button {
    width: 545px;
    height: 84px;
    border-radius: 12px;
    font-size: 20px;
    border: 2px solid;
    margin-top: 32px;
  }

  button:hover {
    transition-duration: 0.5s;
    background-color: #F3F3F3;
  }

</style>