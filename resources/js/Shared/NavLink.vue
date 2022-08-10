<template>
	<Link
		class=""
		:class="{'font-bold border-b p-1': active}"
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