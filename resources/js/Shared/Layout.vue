<template>

	<section class="bg-greesn-100">
		<header class="flex justify-between items-center px-12">
			<p class="tracking-wider text-sm font-bold text-gray-400">A DESIGN THINKING AGENCY</p>
			<div class="h-20 z-50">
				<NavLink href="/" class="uppercase text-3xl font-semibold tracking-wider">
					<img class="-mt-5 h-56 hover:scale-125 transition ease-in delay-100" src="@/../assets/images/stratix_logo/STRATIX_LOGO_BLACK_ON_WHITE.svg">
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

</template>

<script setup>
import Nav from '../Shared/Nav';
import NavLink from "../Shared/NavLink";
import { computed } from "vue";

const year = computed(()=> {
	return new Date().getFullYear();
})

</script>