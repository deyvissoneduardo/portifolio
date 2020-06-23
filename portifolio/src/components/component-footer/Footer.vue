<template>
  <fragment>
    <section id="contato" class="contato">
      <h2>Contato</h2>
      <article>
        <a href="https://github.com/deyvissoneduardo">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="-2 -2 24 24"
            width="50"
            height="50"
            preserveAspectRatio="xMinYMin"
            class="jam jam-github-circle"
          >
            <path
              d="M8.18 15.008c.12 0 .211-.004.271-.012a.317.317 0 0 0 .18-.107c.06-.063.09-.154.09-.274l-.004-.557c-.003-.355-.004-.637-.004-.844l-.188.033a2.41 2.41 0 0 1-.455.028 3.498 3.498 0 0 1-.57-.057 1.276 1.276 0 0 1-.548-.246 1.04 1.04 0 0 1-.36-.503l-.082-.189a2.046 2.046 0 0 0-.258-.417.989.989 0 0 0-.357-.312l-.057-.04a.602.602 0 0 1-.106-.1.455.455 0 0 1-.074-.114c-.016-.038-.003-.07.04-.094a.533.533 0 0 1 .238-.037l.164.025c.11.021.245.087.406.196.16.11.293.251.397.426.126.224.277.395.455.512a.964.964 0 0 0 .536.176c.18 0 .336-.013.467-.04a1.63 1.63 0 0 0 .369-.124c.049-.365.182-.647.4-.843a5.61 5.61 0 0 1-.839-.148 3.346 3.346 0 0 1-.77-.32 2.204 2.204 0 0 1-.66-.548c-.174-.219-.317-.505-.43-.86a4.09 4.09 0 0 1-.167-1.229c0-.66.216-1.223.647-1.687-.202-.497-.183-1.054.057-1.671.159-.05.394-.013.705.11.311.123.54.228.684.316.145.087.26.16.348.22a5.814 5.814 0 0 1 1.573-.212c.54 0 1.065.07 1.573.213l.31-.197c.214-.13.465-.251.754-.36.29-.11.511-.14.664-.09.246.617.268 1.174.065 1.67.432.465.648 1.027.648 1.688 0 .464-.056.875-.168 1.233-.112.358-.257.644-.434.86a2.29 2.29 0 0 1-.664.545 3.342 3.342 0 0 1-.77.32 5.605 5.605 0 0 1-.84.147c.284.245.426.633.426 1.163v1.957c0 .093.014.168.041.226a.226.226 0 0 0 .131.119c.06.021.114.035.16.04.047.006.113.009.2.009h-1.966-2.227z"
            />
            <path
              d="M10 18a8 8 0 1 0 0-16 8 8 0 0 0 0 16zm0 2C4.477 20 0 15.523 0 10S4.477 0 10 0s10 4.477 10 10-4.477 10-10 10z"
            />
          </svg>
        </a>
        <a href="https://www.instagram.com/deyvisson_eduardo/" target="_blank">
          <i class="fab fa-instagram"></i>
        </a>
        <a href="https://api.whatsapp.com/send?phone=5561993240429" target="_blank">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="-2 -2 24 24"
            width="50"
            height="50"
            preserveAspectRatio="xMinYMin"
            class="jam jam-whatsapp"
          >
            <path
              d="M9.516.012C4.206.262.017 4.652.033 9.929a9.798 9.798 0 0 0 1.085 4.465L.06 19.495a.387.387 0 0 0 .47.453l5.034-1.184a9.981 9.981 0 0 0 4.284 1.032c5.427.083 9.951-4.195 10.12-9.58C20.15 4.441 15.351-.265 9.516.011zm6.007 15.367a7.784 7.784 0 0 1-5.52 2.27 7.77 7.77 0 0 1-3.474-.808l-.701-.347-3.087.726.65-3.131-.346-.672A7.62 7.62 0 0 1 2.197 9.9c0-2.07.812-4.017 2.286-5.48a7.85 7.85 0 0 1 5.52-2.271c2.086 0 4.046.806 5.52 2.27a7.672 7.672 0 0 1 2.287 5.48c0 2.052-.825 4.03-2.287 5.481z"
            />
            <path
              d="M14.842 12.045l-1.931-.55a.723.723 0 0 0-.713.186l-.472.478a.707.707 0 0 1-.765.16c-.913-.367-2.835-2.063-3.326-2.912a.694.694 0 0 1 .056-.774l.412-.53a.71.71 0 0 0 .089-.726L7.38 5.553a.723.723 0 0 0-1.125-.256c-.539.453-1.179 1.14-1.256 1.903-.137 1.343.443 3.036 2.637 5.07 2.535 2.349 4.566 2.66 5.887 2.341.75-.18 1.35-.903 1.727-1.494a.713.713 0 0 0-.408-1.072z"
            />
          </svg>
        </a>
      </article>
    </section>

    <footer>
      <p>Todos os direitos reservados &copy; Deyvisson Eduardo</p>
    </footer>
  </fragment>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style>
.contato a {
  color: black;
  text-decoration: none;
}

.contato h2 {
  margin-bottom: 1em;
  text-align: center;
  color: #f2f2f2;
  text-shadow: 2px 2px black;
}

@media (min-width: 640px) {
  .contato {
    padding-top: 0.5em;
    padding-bottom: 2em;
  }

  .contato h3 {
    padding-left: 2em;
    font-size: 1.5em;
  }

  .contato a {
    font-size: 1.5em;
  }
}

@media (min-width: 940px) {
  .contato h3 {
    padding-left: 3em;
    font-size: 2em;
  }
}

@media (min-width: 1240px) {
  .contato h3 {
    padding-left: 5em;
  }
}

.contato {
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

.contato a {
  padding: 0.5em;
  transition: color, 0.5s;
}

.contato a:hover {
  color: #f2f2f2;
}

footer {
  color: black;
  padding-top: 10px;
  padding-bottom: 10px;
  font-family: "Jost", sans-serif;
  display: flex;
  justify-content: center;
  background-color: #f2f2f2;
  font-weight: bold;
}
</style>