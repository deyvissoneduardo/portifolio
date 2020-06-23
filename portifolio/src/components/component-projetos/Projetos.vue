<template>
  <section id="portfolio-projects" class="portfolio-projects">
    <h2 class="portfolio-projects-tecnologias">Projetos Pessoais</h2>
    <div class="grid">
      <!--Cadastro de Usuario-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="CadUsuario" alt="Cadasdro de Usuario" class="img-portfolio-projects" />
              <p>Cadastro de Usuario</p>
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title">Tecnologias utilizadas:</p>
            <ul class="ul-api">
              <li class="card-back-list">Json-Server</li>
              <li class="card-back-list">Axios</li>
              <li class="card-back-list">Bootstrap</li>
              <li class="card-back-list">ReactJS</li>
              <hr />
              <a class="card-back-a" href="https://github.com/deyvissoneduardo/Cadastro-de-Usuario">
                Acesse o projeto no GitHub
                <i class="fab fa-github-alt"></i>
              </a>
            </ul>
          </div>
        </div>
      </div>
      <!--Cadastro de Produtos-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="CadProdutos" alt="Cadastro de Produtos" class="img-portfolio-projects" />
              <p>Cadastro de Produtos</p>
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title">Tecnologias utilizadas:</p>
            <ul class="ul-machupicchu">
              <li class="card-back-list">Json-Server</li>
              <li class="card-back-list">Angular 9</li>
              <li class="card-back-list">Typescript</li>
              <hr />
              <a class="card-back-a" href="https://github.com/deyvissoneduardo/Angular">
                Acesse o
                projeto no GitHub
                <i class="fab fa-github-alt"></i>
              </a>
            </ul>
          </div>
        </div>
      </div>
      <!--Cripotografador-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="Criptografador" alt="Criptografia" class="img-portfolio-projects" />
              <p>Criptografador</p>
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title">Tecnologias utilizadas:</p>
            <ul class="ul-machupicchu">
              <li class="card-back-list">Google Fonts</li>
              <li class="card-back-list">HTML 5</li>
              <li class="card-back-list">CSS 4</li>
              <li class="card-back-list">JavaScript</li>
              <hr />
              <a class="card-back-a" href="https://github.com/deyvissoneduardo/Criptografador">
                Acesse o
                projeto no GitHub
                <i class="fab fa-github-alt"></i>
              </a>
            </ul>
          </div>
        </div>
      </div>
      <!--Electron js-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img
                :src="Electron"
                alt="Aplicação Desktop com EletronJS"
                class="img-portfolio-projects"
              />
              <p>Aplicação Desktop com EletronJS</p>
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title">Tecnologias utilizadas:</p>
            <ul class="ul-api">
              <li class="card-back-list">VueJS</li>
              <li class="card-back-list">Vuetify</li>
              <li class="card-back-list">Electron</li>
              <li class="card-back-list">Sass</li>
              <hr />
              <a class="card-back-a" href="https://github.com/deyvissoneduardo/VueJS">
                Acesse o projeto no GitHub
                <i class="fab fa-github-alt"></i>
              </a>
            </ul>
          </div>
        </div>
      </div>
      <!--Valid-Form-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="ValidForm" alt="Valida Formulario" class="img-portfolio-projects" />
              <p>Valida Formulário</p>
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title">Tecnologias utilizadas:</p>
            <ul class="ul-api">
              <li class="card-back-list">HTML 5</li>
              <li class="card-back-list">JavaScript</li>
              <li class="card-back-list">CSS 4</li>
              <hr />
              <a
                class="card-back-a"
                href="https://github.com/deyvissoneduardo/Valid-Cpf/tree/master/validClass"
              >
                Acesse o projeto no GitHub
                <i class="fab fa-github-alt"></i>
              </a>
            </ul>
          </div>
        </div>
      </div>
      <!--Gerador Senha-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="Gerador" alt="Gerador de Senha" class="img-portfolio-projects" />
              <p>Gerador de Senha</p>
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title">Tecnologias utilizadas:</p>
            <ul class="ul-api">
              <li class="card-back-list">Webpack</li>
              <li class="card-back-list">HTML 5</li>
              <li class="card-back-list">JavaScript</li>
              <li class="card-back-list">CSS 4</li>
              <hr />
              <a class="card-back-a" href="https://github.com/deyvissoneduardo/Gerador-de-Senha">
                Acesse o projeto no GitHub
                <i class="fab fa-github-alt"></i>
              </a>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import CadUsuario from "../../assets/projects/cadastro_usuario.jpg";
import CadProdutos from "../../assets/projects/cadastro_produtos.jpg";
import Criptografador from "../../assets/projects/criptografador.jpg";
import ValidForm from "../../assets/projects/valid_form.jpg";
import Gerador from "../../assets/projects/gera.jpg";
import Electron from "../../assets/projects/electron.jpg";

export default {
  name: "Projetos",
  data: () => {
    return {
      CadUsuario: CadUsuario,
      CadProdutos: CadProdutos,
      Criptografador: Criptografador,
      ValidForm: ValidForm,
      Gerador: Gerador,
      Electron: Electron
    };
  }
};
</script>


<style>
.img-portfolio-projects {
  width: 260px;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.portfolio-projects {
  background-color: gray;
  padding-top: 2rem;
  padding-left: 2em;
  padding-right: 2em;
  padding-bottom: 2em;
  margin-bottom: 1em;
  margin-left: 0.8em;
  margin-right: 0.8em;
}

.portfolio-projects a {
  color: black;
  text-decoration: none;
}

.flip-card {
  background-color: transparent;
  height: 212px;
  border-radius: 1px;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.1s;
  transform-style: preserve-3d;
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front,
.flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-card-back {
  background-color: dodgerblue;
  height: 212px;
  border-radius: 10px;
  color: black;
  transform: rotateY(180deg);
}

@media (min-width: 500px) {
  .flip-card-back {
    margin-left: 0em;
    padding-right: 0em;
  }
}

.card-back-title {
  font-size: 1em;
  color: #f2f2f2;
  padding-bottom: 0.5em;
}

.card-back-title-lg {
  font-size: 1em;
  color: #f2f2f2;
  padding-bottom: 0.5em;
  text-shadow: 1px 1px black;
}

.card-back-subtitle {
  font-size: 1em;
  color: #f2f2f2;
  text-shadow: 1px 1px black;
}

.card-back-list {
  list-style: none;
}

.flip-card-back hr {
  margin-bottom: 5px;
}

.card-back-a {
  transition: color, font-size, 0.5s;
}

.card-back-a:hover {
  font-size: 1.2em;
  color: #00029f;
}

.portfolio-projects h2 {
  padding-bottom: 1em;
  margin-bottom: 0.1em;
  text-align: center;
  color: #f2f2f2;
  text-shadow: 2px 2px black;
}

.portfolio-projects h3 {
  margin-top: 2em;
  margin-bottom: 1em;
  text-align: center;
  color: #f2f2f2;
  text-shadow: 2px 2px black;
}

.portfolio-projects figure {
  text-align: center;
}

.grid {
  display: grid;
  grid-gap: 2rem;
  border-radius: 20px;
}
.outer {
  width: 180px;
  height: 85px;
  border: 5px solid #121212;
  display: flex;
  margin-left: 25%;
  padding: 5px;
  margin-top: 1em;
  margin-bottom: 1em;
  border-radius: 5px;
  box-shadow: 0px 3px 5px 3px gray;
  cursor: pointer;
  transition: all 0.3s;
}
.inner {
  height: 100%;
  background-color: black;
  flex: 1;
  border-radius: 2px;
  opacity: 0;
  animation: ani1 2.5s both;
}

.inner-disable {
  height: 100%;
  background-color: transparent;
  flex: 1;
  border-radius: 2px;
  opacity: 0;
  animation: ani1 2.5s both;
}

.outer:hover {
  border: 5px solid #00029f;
  box-shadow: 0px 3px 5px 3px #482ef2;
}
.outer:hover .inner {
  background: rgb(2, 0, 36);
  background: linear-gradient(
    180deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(9, 41, 121, 1) 100%,
    rgba(0, 212, 255, 1) 100%
  );
}
.inner:nth-child(2) {
  margin: 0 4px;
  animation: ani2 3s 4s both;
}
.inner:nth-child(3) {
  animation: ani3 3s 6s both;
}

@keyframes ani1 {
  33%,
  100% {
    opacity: 1;
  }
}
@keyframes ani2 {
  0%,
  33% {
    opacity: 0;
  }
  66%,
  100% {
    opacity: 1;
  }
}
@keyframes ani3 {
  0%,
  66% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@media (min-width: 375px) {
  .grid figcaption {
    color: whitesmoke;
  }
}

@media (min-width: 640px) {
  .grid {
    grid-template-columns: 260px 260px;
    justify-content: center;
  }

  .outer {
    margin-left: 15%;
  }

  .grid figcaption {
    margin-top: -23px;
    padding-top: 18px;
    padding-bottom: 50px;
    background-color: whitesmoke;
    border-radius: 10px;
    color: black;
  }

  .portfolio-projects figure {
    box-shadow: 3px 3px 6px black;
    border-radius: 10px;
  }
}

@media (min-width: 940px) {
  .grid {
    column-gap: 8em;
    justify-content: center;
  }
}

@media (min-width: 1240px) {
  .grid {
    column-gap: 2em;
    grid-template-columns: 260px 260px 260px 260px;
    justify-content: center;
  }
  .container {
    width: 1280px;
    margin-left: auto;
    margin-right: auto;
  }
}
</style>