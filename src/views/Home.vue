<template>
  <header>
    <nav>
      <ul>
        <li>
          <figure>
            <a href="/"><router-link to="/"></router-link><img class="img-logo" alt="Bet365 logo" src="../assets/bet365-logo.png"></a>
          </figure>
        </li>
        <li>
          <span>Idioma Español</span>
        </li>
        <li>
          <a href="/main"><router-link to="/main"></router-link>Acceder a la pagina</a>
        </li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <article>
        <h4>Bonus de Ingreso</h4>
        <p>Créditos de apuesta, hasta 100€</p>
        <h6>Para clientes nuevos</h6>
        <a href="">Ver últimas cuotas</a>
        <p>Ingreso mí. 5€. Créd. de apuesta  dispon. una vez determinadas las apuestas
        del valor de su ingreso válido. Se aplican cuotas mín., exclusiones de apuesta y métodos de pago.
        Gana. excluyen imp. de créd. de apuesta. Ver lím. de tiempo y condiciones.</p>
      </article>

      <article>
        <figure>
          <img src="../assets/playersMain.png" alt="">
        </figure>
      </article>

      <article>
        <h2>Cómo funciona la oferta</h2>
        <div>
          <h5>Ingresar</h5>
        </div>

        <div>
          <h5>Cómo liberar sus créditos de apuesta</h5>
        </div>

        <div>
          <h5>Cómo utilizar los créditos de apuesta</h5>
        </div>

        <a href="">Ver ultimas cuotas</a>
      </article>
    </section>

    <hr>
  </main>

  <footer>
    <h3>bet365</h3>

    <nav>
      <ul>
        <li>
          <a href="">Ayuda</a>
        </li>

        <li>
          <a href="">Banca</a>
        </li>

        <li>
          <a href="">Contáctenos</a>
        </li>

        <li>
          <a href="">Juego responsable</a>
        </li>

        <li>
          <a href="">Afiliados</a>
        </li>

        <li>
          <a href="">Noticias</a>
        </li>

        <li>
          <a href="">Reclamaciones</a>
        </li>

        <li>
          <a href="">Condiciones generales</a>
        </li>

        <li>
          <a href="">Información de empresa</a>
        </li>

        <li>
          <a href="">Politica de privacidad</a>
        </li>
      </ul>
    </nav>
  </footer>
    
</template>

<script>
// @ is an alias to /src


export default {
  name: 'Home',
  components: {
    
  }
}
</script>

<style scoped>
  header nav ul {
    width: 100vw;
    height: 10vh;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: var(--main-color);
  
  }

  header nav ul li:nth-child(2) {
    color: white;
    margin-right: 0;
  }

  header nav ul li:nth-child(3) {
    border: 1px solid white;
    padding: 1.5vh;
    margin-right: 25vw;
  }

  .img-logo {
    width: 12vw;
  }

  main {
    height: 200vh;
  }

  main section {
    height: 110vh;
    width: 100vw;
    display: grid;
    grid-template-areas:
        "h h1"
        "m m";
    grid-template-columns: 25vw 75vw;
    grid-template-rows: 100vh 25vh;
  }

  main section article:first-child {
    display: grid;
    grid-area: "h";
  }

  main section article:nth-child(2) {
    display: grid;
    grid-area: "h1";
  }

  main section article:nth-child(2) figure img {
    height: 100vh;
  }

  main section article:nth-child(3) {
    display: grid;
    grid-area: "m";
  }

  footer {
    height: 25vh;
  }

</style>
