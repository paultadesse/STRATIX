<template>
	<nav>
		<li class="list-none space-x-12 uppercase tracking-wider ">
			<NavLink href="/achivments" :active="$page.component === 'Achivments'" class="hover:font-bold" >Works</NavLink>
			<NavLink href="/about" :active="$page.component === 'About'" class="hover:font-bold">About</NavLink>
			<NavLink href="/contact" class="hover:font-bold">Contact</NavLink>
		</li>
	</nav>
</template>

<script setup>
import NavLink from "../Shared/NavLink";
</script>

<style lang="css" scoped>
</style>