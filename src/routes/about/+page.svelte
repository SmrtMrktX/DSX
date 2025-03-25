<script>
  import BtnBack from '$lib/components/homeComponents/BtnBack.svelte';
import smxLogo from '$lib/images/logo/smx.png';
</script>




<div class="container myabout">


	<header class=" justify-center m-auto py-10 text-center">
		<img class=" rounded-t-sm border-b-4 border-green-500" src={smxLogo} alt="smx logo" />
	</header>

	<section class=" px-4 py-12 text-center">
		<h2 class="text-2xl font-bold">Mission And Values</h2>
		<p class="mx-auto mt-4 max-w-3xl tracking-wider">
			Our mission is to revolutionize digital marketplaces by offering seamless access, reliable
			performance, and unwavering support, enabling businesses to thrive with cutting-edge,
			efficient solutions.
		</p>
		<div class="animate-fadeIn mt-8 flex justify-center space-x-8">
			<div class="transform transition hover:scale-110">
				<h3 class="text-xl font-bold">5+</h3>
				<p class="">Specialists</p>
			</div>
			<div class="transform transition hover:scale-110">
				<h3 class="text-xl font-bold">3+</h3>
				<p class="">Years of Experience</p>
			</div>
		</div>
	</section>

	<section class=" px-4 py-6">
		<h2 class="text-center text-2xl font-bold">Our Vision</h2>
		<p class="mx-auto mt-4 max-w-2xl text-center tracking-widest">
			We imagine a future where digital marketplaces are more intelligent, accessible, and
			versatile. Our aim is to create a platform that evolves with technology, empowering businesses
			and individuals to excel in an ever-evolving digital landscape.
		</p>
	</section>


<BtnBack />


</div>

<style>




</style>

