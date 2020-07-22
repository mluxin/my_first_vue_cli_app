<script>
import Navigation from './components/Navigation.vue'

export default {
	name: 'App',
	components: {
		Navigation
  }
}
</script>

<template>
	<div id="app">
		<nav>
			<Navigation url="/" text="Accueil" />
			<Navigation url="/about" text="À propos" />
			<Navigation url="/contact" text="Contact" />
		</nav>
		<p>Bienvenue sur notre page d'<Navigation /></p>
	</div>
</template>


<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
