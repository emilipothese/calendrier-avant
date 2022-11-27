<template>
  <section>
    <aside>
      <h1>Jour 1</h1>
      <p>La surprise est proposée par Ulla Nidegger</p>
      <small>Recette de Cookies</small>
      <img class="card__team" src="../assets/Donuts_Team_Ulla Nidegger_PosterImage.png" alt="">
    </aside>

    <main>
      <button>Découvrez la recette ici!</button>
    </main>
  </section>
</template>

<style scoped>
  section {
    background-color: #28AB67;
    display: flex;
    align-items: flex-end;
    color: black;
  }

  aside {
    text-align: left;
    display: flex;
    flex-direction: column;
    padding: 1.2em;
  }

  h1 {
    font-size: 3.3em;
    line-height: 1.5;
    margin: 0;
  }

  p {
    margin: 0.5em 0 0 0;
  }

  .card__team {
    width: 60%;
  }

  main {
    flex-grow: 2;
    padding: 1.2em;
    background-image: url('../assets/EasyChristmasSugarCookies_188693_02-scaled.png');
    background-size: cover;
    height: 350px;
  }
</style>
