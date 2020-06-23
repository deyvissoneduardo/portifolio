<template>
  <section id="sobre" class="sobre">
    <div class="container">
      <!-- about me-->
      <h2>Sobre mim</h2>
      <figure>
        <img :src="Photo" class="avatar" alt="Deyvisson Eduardo" />
      </figure>
      <p>
        Deyvisson Eduardo Almeida, Desenvolvedor Junior no início de sua carreira como desenvolvedor Web e
        Mobile .
      </p>
      <p>
        Formado em Analise e Desenvolvimento de Sistemas pela Faculdade Tecnologica Senac 903 Sul, apaixonado
        por tecnologia desde aproximadamente 2010,
        mas foi em 2018 que iniciei o curso com o intuito de apronfunda conhecimentos na area de
        desenvolvimento.
      </p>
      <p>
        A partir desse ponto foquei em aperfeiçoar as melhores tecnologias para o desenvolvimento web, como o
        PHP e JavaScript, juntamente aos framework
        Angular, VueJS, Bootstrap. E também no desenvolvimento mobile nas linguagens de programação Kotlin e
        Flutter.
      </p>
      <p>
        Me identifico como uma pessoa extrovertida, com facil comunicação e aprendizado. Movido por desafios e
        solução de problemas,
        acredito que essas características agregado a habilidades técnicas, são fundamentais para
        desenvolvedores no cenário atual.
      </p>
      <p>
        Sigo diariamente em busca conhecimentos e adquirir novas habilidades que possam agragar positivamente em
        meus
        conhecimentos em inicio de carreira.
      </p>
    </div>
  </section>
</template>

<script>
import Photo from '../../assets/body/photo.jpg'

export default {
  name: "Body",
  data: () => {
        return {
            Photo: Photo
        }
    }
};
</script>

<style>
.container {
  width: 1280px;
  margin-left: auto;
  margin-right: auto;
}
body {
  background: rgb(2, 0, 36);
  background: linear-gradient(
    193deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(9, 41, 121, 1) 44%,
    rgba(0, 212, 255, 1) 100%
  );
  color: #f2f2f2;
  font-size: 1.1rem;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
#sobre {
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

.sobre p {
  text-indent: 1em;
  text-align: justify-self; 
}

.sobre h2 {
  margin-bottom: 1em;
  text-align: center;
  color: #f2f2f2;
  text-shadow: 2px 2px black;
}

.avatar {
  margin-left: 5em;
  margin-right: 5em;
  border: solid 5px transparent;
  border-radius: 20px;
  float: left;
  margin-bottom: 20px;
  height: 380px;
}
@media (min-width: 1357px) {
  .avatar {
    margin-top: 0px;
  }
}

@media (min-width: 1387px) {
  .avatar {
    margin-top: -2em;
    margin-bottom: 1px;
    height: 250px;
  }
}
@media (min-width: 376px) {
  .avatar {
    margin-left: 4em;
  }
}

@media (min-width: 415px) {
  .sobre p {
    font-size: 1.3em;
  }
}
</style>