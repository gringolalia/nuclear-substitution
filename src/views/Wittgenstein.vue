<template lang="pug">
.home
	img(alt='Spectre of Communism' src='../assets/img/hammer-sickle.svg' width='222px')
	HelloWorld
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
	name: 'home',
	components: {
		HelloWorld
	}
}
</script>

<style>

.home {
	min-height: 100vh;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}

</style>