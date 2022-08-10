<template>
	<div class="relative">
	<section class="">
		<header class="flex justify-between items-center px-12 py-6">
			<div class="border border-8 border-black px-2">
				<NavLink href="/" class="uppercase text-5xl font-semibold">
					Stratix
				</NavLink>
			</div>
			<hr class="w-1/2">
			<Nav />
		</header>
	</section>

	<section>
		<div class="py-6">
			<slot/>
		</div>
	</section>

	</div>
</template>

<script setup>
import Nav from '../Shared/Nav';
import NavLink from "../Shared/NavLink";

</script>