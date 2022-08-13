<template>

	<section class="bg-greesn-100">
		<header class="flex justify-between items-center px-6 xl:px-12">

			<p class="hidden xl:block tracking-wider text-sm font-bold text-gray-400">A DESIGN THINKING AGENCY</p>

			<div class="h-20 z-50 xl:-mr-20">
				<NavLink href="/" class="uppercase text-3xl font-semibold tracking-wider">
					<img class="xl:-mt-5 h-32 xl:h-56 hover:scale-125 transition ease-in delay-100" src="@/../assets/images/stratix_logo/STRATIX_LOGO_BLACK_ON_WHITE.svg">
				</NavLink>
			</div>

			<div>
				<div class="relative z-50 xl:hidden">
					<button v-if="toggleMenuActive" @click="toggleMenuActive = false" tabindex="-1" class="fixed top-0 right-0 bottom-0 left-0 bg-black opacity-50 cursor-default"></button>
					<svg v-if="!toggleMenuActive" @click="toggleMenuActive = true" xmlns="http://www.w3.org/2000/svg" class="h-9 w-9 xl:hidden" fill="none" viewBox="0 0 24 24" 	stroke="currentColor" stroke-width="2">
  						<path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" />
					</svg>
					<svg v-if="toggleMenuActive" @click="toggleMenuActive = false" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
  						<path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
					</svg>
					<div v-if="toggleMenuActive" class="absolute top-10 right-0 border p-8 bg-white">
						<div @click="toggleMenuActive = false">
							<Nav />
						</div>
					</div>
				</div>
				<Nav class="hidden xl:block" />
			</div>

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
import { ref, computed } from "vue";


let toggleMenuActive = ref(false)

const year = computed(()=> {
	return new Date().getFullYear();
})

</script>