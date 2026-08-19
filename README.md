<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>6855 Demo</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #efffea;
  color: #555;
  padding-bottom: 80px;
}

header {
  height: 80px;
  background: #fff34d;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 15px;
}

.logo {
  font-size: 38px;
  font-weight: 900;
  color: #173d2c;
}

.logo span {
  color: #19b457;
}

.demo {
  font-size: 10px;
  font-weight: bold;
  background: #d9ff9d;
  padding: 6px;
  border-radius: 7px;
}

.balance {
  background: white;
  border: 2px solid #16b85c;
  border-radius: 12px;
  padding: 7px 10px;
  color: #16854b;
  font-weight: bold;
  font-size: 12px;
}

.hero {
  margin: 15px;
  height: 175px;
  border-radius: 14px;
  background: linear-gradient(135deg,#ffbd25,#ff5e18);
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
}

.hero b {
  font-size: 32px;
  text-shadow: 2px 3px #9c280e;
}

.hero span {
  display: block;
  margin-top: 8px;
}

.promos {
  display: grid;
  grid-template-columns: repeat(3,1fr);
  gap: 8px;
  padding: 0 15px;
}

.promo {
  background: linear-gradient(#f7ff3e,#b7f229);
  border-radius: 12px;
  padding: 13px 5px;
  text-align: center;
  color: #176b3e;
  font-weight: bold;
  font-size: 12px;
}

.promo strong {
  display: block;
  font-size: 19px;
  color: #e53b21;
  margin-top: 5px;
}

.notice {
  margin: 15px;
  padding: 17px;
  background: white;
  border-radius: 14px;
  color: #397454;
}

.section {
  padding: 0 15px;
}

.title {
  display: flex;
  justify-content: space-between;
  margin: 18px 0 12px;
  color: #176f46;
  font-size: 21px;
  font-weight: bold;
}

.games {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 10px;
}

.game {
  height: 155px;
  border-radius: 14px;
  display: flex;
  align-items: flex-end;
  padding: 12px;
  color: white;
  font-size: 19px;
  font-weight: bold;
  text-shadow: 1px 2px 3px #000;
}

.game1 {
  background: linear-gradient(135deg,#ff9d1c,#d52e20);
}

.game2 {
  background: linear-gradient(135deg,#9c49ff,#2436a8);
}

.game3 {
  background: linear-gradient(135deg,#15c9a2,#2451c7);
}

.game4 {
  background: linear-gradient(135deg,#ff4a77,#6c1db6);
}

.page {
  display: none;
}

.page.active {
  display: block;
}

.profile {
  padding: 20px 15px;
}

.profileBox {
  background: linear-gradient(135deg,#ffe94c,#c9ff59);
  border-radius: 18px;
  padding: 25px;
  text-align: center;
}

.avatar {
  width: 90px;
  height: 90px;
  margin: auto;
  border-radius: 22px;
  background: #16b85c;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 40px;
  font-weight: bold;
}

.username {
  font-size: 24px;
  font-weight: bold;
  margin: 10px;
}

.vip {
  margin-top: 18px;
  background: #10b45a;
  color: white;
  border-radius: 14px;
  padding: 16px;
  text-align: left;
}

.progress {
  height: 11px;
  background: #bdebc7;
  border-radius: 20px;
  overflow: hidden;
  margin-top: 12px;
}

.progress div {
  width: 70%;
  height: 100%;
  background: #20c68b;
}

.list {
  margin-top: 15px;
  background: white;
  border-radius: 14px;
}

.row {
  padding: 18px;
  border-bottom: 1px solid #eee;
  display: flex;
  justify-content: space-between;
}

nav {
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  height: 75px;
  background: #e5ff83;
  display: grid;
  grid-template-columns: repeat(5,1fr);
  z-index: 10;
}

nav button {
  border: 0;
  background: none;
  color: #25824f;
  font-weight: bold;
  font-size: 11px;
}

nav button b {
  display: block;
  font-size: 23px;
  margin-bottom: 4px;
}

.activeNav {
  color: #0b9e50 !important;
}
</style>
</head>

<body>

<header>
  <div class="logo">
    6855<span>+</span>
  </div>

  <div class="demo">
    DEMO
  </div>

  <div class="balance">
    Saldo<br>
    <b id="saldo">R$ 0,16</b>
  </div>
</header>

<section id="home" class="page active">

  <div class="hero">
    <div>
      <b>ECONOMIA DE 25%</b>
      <span>Área promocional de demonstração</span>
    </div>
  </div>

  <div class="promos">
    <div class="promo">
      CONVIDE
      <strong>+58 pts</strong>
    </div>

    <div class="promo">
      DESAFIO
      <strong>+100 pts</strong>
    </div>

    <div class="promo">
      BÔNUS
      <strong>SEMANAL</strong>
    </div>
  </div>

  <div class="notice">
    🔔 Bem-vindo ao protótipo! Todos os valores e recompensas são fictícios.
  </div>

  <div class="section">

    <div class="title">
      🔥 Conteúdos em destaque
    </div>

    <div class="games">

      <div class="game game1">
        Fortune Tiger
      </div>

      <div class="game game2">
        Fortune Rabbit
      </div>

      <div class="game game3">
        Fortune Dragon
      </div>

      <div class="game game4">
        Fortune Horse
      </div>

    </div>

  </div>

</section>

<section id="promo" class="page">

  <div class="profile">

    <div class="title">
      🎁 Promoções
    </div>

    <div class="list">

      <div class="row">
        <span>Desafio diário</span>
        <b>+20 pts</b>
      </div>

      <div class="row">
        <span>Visita diária</span>
        <b>+10 pts</b>
      </div>

      <div class="row">
        <span>Conquista semanal</span>
        <b>+50 pts</b>
      </div>

    </div>

  </div>

</section>

<section id="progresso" class="page">

  <div class="profile">

    <div class="title">
      📊 Progresso
    </div>

    <div class="profileBox">

      <h2>Pontuação de demonstração</h2>

      <h1>160 pontos</h1>

      <div class="progress">
        <div></div>
      </div>

      <p>160 / 300 pontos</p>

    </div>

  </div>

</section>

<section id="carteira" class="page">

  <div class="profile">

    <div class="title">
      💳 Carteira fictícia
    </div>

    <div class="profileBox">

      <h3>Saldo demonstrativo</h3>

      <h1>R$ 0,16</h1>

      <p>Nenhum depósito ou saque é realizado.</p>

    </div>

  </div>

</section>

<section id="perfil" class="page">

  <div class="profile">

    <div class="profileBox">

      <div class="avatar">
        A
      </div>

      <div class="username" id="nome">
        Visitante
      </div>

      <p>
        Saldo fictício:
        <b>R$ 0,16</b>
      </p>

      <div class="vip">

        <h2>Nível 2</h2>

        <p>Progresso de demonstração</p>

        <div class="progress">
          <div></div>
        </div>

      </div>

    </div>

    <div class="list">

      <div class="row">
        <span>👤 Perfil</span>
        <b>›</b>
      </div>

      <div class="row">
        <span>💬 Mensagens</span>
        <b>›</b>
      </div>

      <div class="row">
        <span>🎁 Conquistas</span>
        <b>›</b>
      </div>

    </div>

  </div>

</section>

<nav>

  <button class="activeNav" onclick="abrir('home',this)">
    <b>⌂</b>
    Início
  </button>

  <button onclick="abrir('promo',this)">
    <b>🎁</b>
    Promoção
  </button>

  <button onclick="abrir('progresso',this)">
    <b>📊</b>
    Progresso
  </button>

  <button onclick="abrir('carteira',this)">
    <b>▣</b>
    Carteira
  </button>

  <button onclick="abrir('perfil',this)">
    <b>●</b>
    Perfil
  </button>

</nav>

<script>

function abrir(id,botao){

  document
    .querySelectorAll('.page')
    .forEach(function(p){
      p.classList.remove('active');
    });

  document
    .getElementById(id)
    .classList.add('active');

  document
    .querySelectorAll('nav button')
    .forEach(function(b){
      b.classList.remove('activeNav');
    });

  botao.classList.add('activeNav');

  window.scrollTo(0,0);
}

</script>

</body>
</html>