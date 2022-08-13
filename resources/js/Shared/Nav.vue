<template>
	<nav>
		<li class="list-none flex flex-col xl:block space-y-6 xl:space-y-0 xl:space-x-12 uppercase tracking-wider font-poppins">
			<NavLink href="/works" :active="$page.component === 'Works'" class="hover:text-black font-semibold text-gray-500">Works</NavLink>
			<NavLink href="/about" :active="$page.component === 'About'" class="hover:text-black font-semibold text-gray-500">About</NavLink>
			<NavLink href="/contact" :active="$page.component === 'Contact'" class="hover:text-black font-semibold text-gray-500">Contact</NavLink>
		</li>
	</nav>
</template>

<script setup>
import NavLink from "../Shared/NavLink";
</script>

<style lang="css" scoped>
</style>