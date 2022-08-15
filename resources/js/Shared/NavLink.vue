<template>
	<Link
		class=""
		:class="{'font-bold border-b border-black p-1 text-black': active}"
	>
		<slot />		
	</Link>
</template>

<script setup>
import { Link } from "@inertiajs/inertia-vue3";
import { computed, defineProps } from "vue";

const props = defineProps({
	active: Boolean
})

const active = computed(() => {
	return props.active
})


</script>

<style lang="css" scoped>
</style>