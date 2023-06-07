<script lang="ts">
	import Carousel from '$lib/components/Carousel.svelte';
	import Chat from '$lib/components/Chat.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import HeroLeft from '$lib/components/HeroLeft.svelte';
	import Mobile from '$lib/components/Mobile.svelte';
	import Stats from '$lib/components/Stats.svelte';
	import HeroCards from '$lib/components/HeroCards.svelte';
	import Links from '$lib/components/Links.svelte';
	import Countdown from '$lib/components/Countdown.svelte';
	import Drawer from '$lib/components/Drawer.svelte';
	import Card from '$lib/components/Card.svelte';
	import SimpleCard from '$lib/components/SimpleCard.svelte';
</script>

<div class="bg-base-content pb-2">
	<div class="">
		<div class="">
			<Hero />
		</div>

		<div class="lg:container mx-auto slide">
			<Carousel />
		</div>
	</div>
	<div class="container mx-auto px-3">
		<!-- <Stats /> -->
		<!-- <Chat /> -->
		<!-- <div class="my-10 flex flex-col md:flex-row gap-2 xl:gap-5">
			<Card />
		</div> -->

		<div class="my-10" id="nosotros">
			<SimpleCard />
		</div>

		

		<div class="my-10">
			<HeroLeft />
		</div>

		<!-- <div class="my-10">
			<Links />
		</div> -->
	</div>
</div>
