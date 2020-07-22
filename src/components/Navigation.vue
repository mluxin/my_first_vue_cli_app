// ./components/HomeLink.vue
<script>
export default {
  name: 'Navigation',
  props: ['url', 'text']
}
</script>

<template>
	<a href="url">{{ text }}</a>
</template>

<style>
	a {
		text-decoration: none;
	}
</style>