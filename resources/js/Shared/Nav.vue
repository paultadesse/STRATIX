<template>
	<nav>
		<li class="list-none space-x-12 uppercase font-light tracking-wider">
			<NavLink href="/achivments" :active="$page.component === 'Achivments'">Achivments</NavLink>
			<NavLink href="/about" :active="$page.component === 'About'">About</NavLink>
			<NavLink href="/">Contact</NavLink>
		</li>
	</nav>
</template>

<script setup>
import NavLink from "../Shared/NavLink";
</script>

<style lang="css" scoped>
</style>