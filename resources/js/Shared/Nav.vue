<template>
	<nav>
		<li class="list-none space-x-12 uppercase tracking-wider ">
			<!-- <NavLink href="/achivments" :active="$page.component === 'Achivments'" class="hover:font-bold" >Works</NavLink> -->
			<NavLink href="/about" :active="$page.component === 'About'" class="hover:text-black font-bold text-gray-500">About</NavLink>
			<NavLink href="/contact" :active="$page.component === 'Contact'" class="hover:text-black font-bold text-gray-500">Contact</NavLink>
		</li>
	</nav>
</template>

<script setup>
import NavLink from "../Shared/NavLink";
</script>

<style lang="css" scoped>
</style>