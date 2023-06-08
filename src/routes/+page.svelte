<script lang="ts">
	import Carousel from '$lib/components/Carousel.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import HeroLeft from '$lib/components/HeroLeft.svelte';
	import SimpleCard from '$lib/components/SimpleCard.svelte';
</script>

<div class="bg-base-content pb-2">
	<div class="">
		<div class="">
			<Hero />
		</div>
		<div class="lg:container mx-auto w-full">
			<Carousel />
		</div>
	</div>
	<div class="container mx-auto px-3">
		<div class="my-10" id="nosotros">
			<SimpleCard />
		</div>
		<div class="my-10">
			<HeroLeft />
		</div>
	</div>
</div>
