html <!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Viagem ao Vilarejo</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- Navegação -->
    <nav>
      <ul>
        <li><a href="#tripme">TripMe</a></li>
        <li><a href="#meetus">MeetUs</a></li>
        <li><a href="#advice">Advice</a></li>
      </ul>
    </nav>

    <!-- Banner -->
    <main>
      <section class="banner" id="home">
        <div class="overlay">
          <h1>Explore o Vilarejo Europeu</h1>
          <p>Viva a experiência única em um lugar encantador!</p>
        </div>
      </section>

      <!-- Seção TripMe -->
      <section id="tripme">
        <h2>TripMe</h2>
        <p>
          Descubra os melhores pontos turísticos e o que você não pode perder em sua visita ao vilarejo.
        </p>
      </section>

      <!-- Seção MeetUs -->
      <section id="meetus">
        <h2>MeetUs</h2>
        <p>
          Conheça a nossa equipe local e o que torna este vilarejo tão especial. Nós te aguardamos!
        </p>
      </section>

      <!-- Seção Advice -->
      <section id="advice">
        <h2>Advice</h2>
        <p>
          Dicas e conselhos essenciais para tornar sua viagem ainda mais inesquecível. Aproveite cada momento!
        </p>
      </section>
    </main>

    <!-- Rodapé -->
    <footer>
      <p>© 2024 Viagem ao Vilarejo. Todos os direitos reservados.</p>
    </footer>
  </body>
</html>







CSS /* Resetando margens e padding */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Estilo da navegação */
nav {
  background-color: #333;
  padding: 10px 0;
  text-align: center;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline;
  margin: 0 20px;
}

nav ul li a {
  text-decoration: none;
  color: white;
  font-size: 18px;
  font-weight: bold;
}

nav ul li a:hover {
  color: #c47e35;
  text-decoration: underline;
}

/* Estilo do banner */
.banner {
  background-image: url('https://via.placeholder.com/1500x800'); /* Substitua com uma imagem real do vilarejo */
  background-size: cover;
  background-position: center;
  height: 400px;
  position: relative;
  color: white;
  text-align: center;
  padding: 80px 20px;
}

.overlay {
  background: rgba(0, 0, 0, 0.5);
  padding: 20px;
}

.banner h1 {
  font-size: 50px;
  margin-bottom: 10px;
}

.banner p {
  font-size: 20px;
}

/* Estilo das seções */
section {
  padding: 50px 20px;
  text-align: center;
}

section h2 {
  font-size: 32px;
  margin-bottom: 20px;
}

section p {
  font-size: 18px;
  line-height: 1.6;
  max-width: 800px;
  margin: 0 auto;
}

/* Estilo do rodapé */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
  position: relative;
  bottom: 0;
  width: 100%;
}

/* Efeito de hover nas seções */
nav ul li a:hover {
  color: #dca15d;
  transition: background-color 0.3s, color 0.3s;
}

/* Responsividade */
@media screen and (max-width: 768px) {
  .banner h1 {
    font-size: 36px;
  }

  .banner p {
    font-size: 18px;
  }

  section h2 {
    font-size: 28px;
  }

  section p {
    font-size: 16px;
  }
}
