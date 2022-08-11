<template>
	<!-- <div class="relative"> -->
	<section class="">
		<header class="flex justify-between items-center px-12 py-6">
			<p class="tracking-wider text-sm font-bold text-gray-400">A DESIGN THINKING AGENCY</p>
			<div class="border border-4 border-black px-4">
				<NavLink href="/" class="uppercase text-3xl font-semibold tracking-wider">
					Stratix
				</NavLink>
			</div>
			<!-- <hr class="w-1/2"> -->
			<Nav />
		</header>
	</section>

	<section>
		<div class="py-6">
			<slot/>
		</div>
	</section>

	<section>
		<div class="py-7 bg-black text-white">
			<div class="flex justify-center">
				<p class="text-sm">© {{ year }} Stratix All rights reserved</p>
			</div>
		</div>
	</section>



	<!-- </div> -->
</template>

<script setup>
import Nav from '../Shared/Nav';
import NavLink from "../Shared/NavLink";
import { computed } from "vue";

const year = computed(()=> {
	return new Date().getFullYear();
})

</script>