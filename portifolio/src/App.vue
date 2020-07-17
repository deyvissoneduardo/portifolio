<template>
  <div id="app">
    <Header />
    <Body />
    <Navigation />
    <Projetos />
    <Footer />
  </div>
</template>

<script>
import Header from './components/components-hearder/Header'
import Body from './components/components-body/Body'
import Navigation from './components/components-navigation/Navigation'
import Projetos from './components/component-projetos/Projetos'
import Footer from './components/component-footer/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Body,
    Navigation,
    Projetos,
    Footer
  },
}
</script>

<style>
</style>
