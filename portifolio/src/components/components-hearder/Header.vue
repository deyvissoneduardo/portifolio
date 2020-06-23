<template>
  <header id="home">
    <nav class="menu">
      <ul>
        <li>
          <a class="scroll menu-list" href="#contato">Contato</a>
        </li>
        <li>
          <a class="scroll menu-list" href="#portfolio">Portfólio</a>
        </li>
        <li>
          <a class="scroll menu-list" href="#sobre">Sobre</a>
        </li>
        <li style="float:left">
          <a class="scroll logo" href="#home">Deyvisson Eduardo</a>
        </li>
      </ul>
    </nav>
    <div class="first-window">
      <h1 class="site-title">Deyvisson Eduardo</h1>
      <h2 class="site-subtitle animação-digitando">Junior Developer</h2>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.site-title {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  text-shadow: 2px 2px black;
}

.site-subtitle {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  text-shadow: 2px 2px black;
  border-right: 2px solid rgba(255, 255, 255, 0.75);
  margin: 0 auto;
  white-space: nowrap;
  overflow: hidden;
}

.animação-digitando {
  animation: digitar 1.5s steps(40) both,
    cursor-transparente 500ms infinite normal;
}

@keyframes digitar {
  0% {
    width: 0ch;
  }
  100% {
    width: 15ch;
  }
}

@keyframes cursor-transparente {
  from {
    border-right-color: rgba(255, 255, 255, 0.75);
  }
  to {
    border-right-color: transparent;
  }
}

@media (min-width: 600px) {
  .menu a {
    font-size: 1.1rem;
  }
  .site-title {
    font-size: 1.1rem;
    text-shadow: 4px 4px black;
  }
}

@media (min-width: 1024px) {
  .menu a {
    font-size: 1.5rem;
  }
  .site-title {
    font-size: 3.2rem;
  }
  .site-subtitle {
    font-size: 2.1rem;
  }
}

header {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.menu {
  background-color: #f2f2f2;
  position: fixed;
  width: 100vw;
  top: 0;
  z-index: 1;
}

.menu ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

.menu li {
  float: right;
}

.logo {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  color: #0466c8;
  text-shadow: 0.5px 0.5px 2px black;
  margin-left: 1em;
  display: block;
  padding-top: 2.5px;
  text-decoration: none;
  transition: color, text-shadow, 0.5s;
}

.logo:hover {
  font-size: 1.5rem;
  color: whitesmoke;
  text-shadow: 2px 2px 3px #0353a4;
}

.menu-list {
  color: black;
  display: block;
  text-decoration: none;
  padding: 5px 15px;
  transition: color, text-shadow, 0.5s;
}

.menu-list:hover {
  background: rgb(2, 0, 36);
  background: linear-gradient(
    180deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(9, 41, 121, 1) 70%,
    rgba(0, 212, 255, 1) 100%
  );
  color: #f2f2f2;
  text-shadow: 1px 1px black;
}

.site-title,
.site-subtitle {
  color: whitesmoke;
  text-align: center;
}
</style>