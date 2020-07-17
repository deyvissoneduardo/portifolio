<template>
  <section id="portfolio-navigation" class="portfolio-navigation">
    <h2 class="portfolio-navigation-tecnologias">Conhecimentos em Programação</h2>
    <div class="grid">
    <!--Languages-->
    <!--PHP-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="PHP" alt="PHP" class="img-portfolio-navigation" />
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title-lg">Nível de domínio:</p>
            <div class="outer">
              <div class="inner"></div>
              <div class="inner"></div>
              <div class="inner"></div>
            </div>
            <p class="card-back-subtitle">Avançado</p>
          </div>
        </div>
      </div>
      <!-- JS -->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="JS" alt="JavaScript" class="img-portfolio-navigation" />
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title-lg">Nível de domínio:</p>
            <div class="outer">
              <div class="inner"></div>
              <div class="inner"></div>
              <div class="inner"></div>
            </div>
            <p class="card-back-subtitle">Avançado</p>
          </div>
        </div>
      </div>
      <!--KOTLIN -->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="KT" alt="Kotlin" class="img-portfolio-navigation" />
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title-lg">Nível de domínio:</p>
            <div class="outer">
              <div class="inner"></div>
              <div class="inner"></div>
              <div class="inner-disable"></div>
            </div>
            <p class="card-back-subtitle">Intermediário</p>
          </div>
        </div>
      </div>
      <!--FLUTTER-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="FLUTTER" alt="Flutter" class="img-portfolio-navigation" />
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title-lg">Nível de domínio:</p>
            <div class="outer">
              <div class="inner"></div>
              <div class="inner"></div>
              <div class="inner-disable"></div>
            </div>
            <p class="card-back-subtitle">Intermediário</p>
          </div>
        </div>
      </div>
      <!--Database-->
      <!--MYSQL-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="MySql" alt="MySql" class="img-portfolio-navigation" />
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title-lg">Nível de domínio:</p>
            <div class="outer">
              <div class="inner"></div>
              <div class="inner"></div>
              <div class="inner-disable"></div>
            </div>
            <p class="card-back-subtitle">Intermediário</p>
          </div>
        </div>
      </div>
      <!--POSTGRES-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="Postgres" alt="PostgresSql" class="img-portfolio-navigation" />
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title-lg">Nível de domínio:</p>
            <div class="outer">
              <div class="inner"></div>
              <div class="inner"></div>
              <div class="inner-disable"></div>
            </div>
            <p class="card-back-subtitle">Intermediário</p>
          </div>
        </div>
      </div>
      <!--FIREBASE-->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="Firebase" alt="Firebase" class="img-portfolio-navigation" />
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title-lg">Nível de domínio:</p>
            <div class="outer">
              <div class="inner"></div>
              <div class="inner"></div>
              <div class="inner-disable"></div>
            </div>
            <p class="card-back-subtitle">Intermediário</p>
          </div>
        </div>
      </div>
      <!-- DOCKER -->
      <div class="flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front">
            <figure>
              <img :src="Docker" alt="Firebase" class="img-portfolio-navigation" />
            </figure>
          </div>
          <div class="flip-card-back">
            <p class="card-back-title-lg">Nível de domínio:</p>
            <div class="outer">
              <div class="inner"></div>
              <div class="inner-disable"></div>
              <div class="inner-disable"></div>
            </div>
            <p class="card-back-subtitle">Básico</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
// languages
import PHP from '../../assets/languages/php.jpg'
import JS from '../../assets/languages/javascript.jpg'
import KT from '../../assets/languages/kotlin.jpg'
import FLUTTER from '../../assets/languages/flutter.jpg'
// database
import MySql from '../../assets/database/mysql.jpg'
import Postgres from '../../assets/database/postgres.jpg'
import Firebase from '../../assets/database/firebase.jpg'
// DevOps
import Docker from '../../assets/devops/docker.jpg'
export default {
  name: "Navigation",
    data: () => {
      return {
        PHP: PHP,
        JS: JS,
        KT: KT,
        FLUTTER: FLUTTER,
        MySql: MySql,
        Postgres: Postgres,
        Firebase: Firebase,
        Docker: Docker
      }
    }
};
</script>

<style>
.img-portfolio-navigation {
  width: 260px;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.portfolio-navigation {
  background-color: gray;
  padding-top: 2rem;
  padding-left: 2em;
  padding-right: 2em;
  padding-bottom: 2em;
  border-radius: 25px;
  margin-bottom: 1em;
  margin-left: 0.8em;
  margin-right: 0.8em;
}

.portfolio-navigation a {
  color: black;
  text-decoration: none;
}

.flip-card {
  background-color: transparent;
  height: 212px;
  border-radius: 10px;
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
  font-size: 1.5em;
  color: #f2f2f2;
  padding-bottom: 0.5em;
  text-shadow: 1px 1px black;
}

.card-back-subtitle {
  font-size: 1.5em;
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

.portfolio-navigation h2 {
  margin-bottom: 1em;
  text-align: center;
  color: #f2f2f2;
  text-shadow: 2px 2px black;
}

.portfolio-navigation h3 {
  margin-top: 2em;
  margin-bottom: 1em;
  text-align: center;
  color: #f2f2f2;
  text-shadow: 2px 2px black;
}

.portfolio-navigation figure {
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

  .portfolio-navigation figure {
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