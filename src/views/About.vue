<template lang="pug">
.container
	img.mt-5(alt='Spectre of Communism' src='../assets/img/hammer-sickle.svg' width='222px')
	h1 Run Silent, Run Deep
	h2 Bertrand Russell on Aboutness
	.d-flex
		button.btn.btn-lg.btn-default.btn-icon-label.mr-2(type='button')
			span.btn-inner--icon
				i.fas.fa-sun
			span.btn-inner--text(style="margin-right: 12px") Pressure

		button.btn.btn-lg.btn-dark.btn-icon-label.mr-2(type='button')
			span.btn-inner--icon
				i.fas.fa-sun
			span.btn-inner--text Coercion

		button.btn.btn-lg.btn-danger.btn-icon-label.mr-2(type='button')
			span.btn-inner--icon
				i.fas.fa-sun
			span.btn-inner--text Stress

	.container
		.row.mt-5
			.col-md-4
				.card.bg-light.text-black.px-4.py-4.border-0.mb-0
					.card-body
						h1.heading.h3.text-grey Queen of Spleen

						p.mt-4.text-left
							i.fas.fa-sun.fa-5x.fa-pull-left
							|	Lorem ipsum dolor sit amet, modo platonem mel an. Sit iuvaret instructior ut, sit sint illum incorrupte eu. Eu feugiat impedit dissentiet pri. Omnium oportere maiestatis eu mel.
						.d-flex
							a.btn.btn-secondary.mt-2.mr-2(href='#') Action Now
							a.btn.btn-dark.mt-2(href='#') Delay

			.col-md-4
				.card.bg-bluegrey.px-4.py-4.border-0.mb-0
					.card-body
						h1.heading.h3 Ace of Face
						p.mt-4.text-left
							i.fas.fa-chess-rook.fa-5x.fa-pull-left
							| Lorem ipsum dolor sit amet, modo platonem mel an. Sit iuvaret instructior ut, sit sint illum incorrupte eu. Eu feugiat impedit dissentiet pri. Omnium oportere maiestatis eu mel.
							
						.d-flex
							a.btn.btn-secondary.mt-2.mr-2(href='#') Action Now
							a.btn.btn-dark.mt-2(href='#') Delay

			.col-md-4
				.card.bg-dark.text-white.px-4.py-4.border-0.mb-0
					.card-body
						h1.heading.h3.text-white King of the Ring
						p.mt-4.text-left
							i.fas.fa-university.fa-5x.fa-pull-left
							|	Lorem ipsum dolor sit amet, modo platonem mel an. Sit iuvaret instructior ut, sit sint illum incorrupte eu. Eu feugiat impedit dissentiet pri. Omnium oportere maiestatis eu mel.
							
						.d-flex
							a.btn.btn-secondary.mt-2.mr-2(href='#') Action Now
							a.btn.btn-dark.mt-2(href='#') Delay


	//- .card.text-white.border-0.overflow-hidden(style="width: 500px")
	//- 	img.card-img(src='https://www.tenne-groebernhof.de/wp-content/uploads/2014/07/placeholder-3x2.jpg'  style="max-width: 100%")
	//- 	span.mask.bg-primary.alpha-7
	//- 	.card-img-overlay.d-flex.align-items-center
	//- 		.col-lg-8
	//- 			h4.heading.h3.text-white The Jack of Smack
	//- 			p.card-text This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.

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
.container {
	min-height: 100vh;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.home {
	min-height: calc(100vh + 75px);
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
</style>