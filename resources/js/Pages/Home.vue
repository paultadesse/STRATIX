<template>
	<div class="relative h-screen">
		<div class="h-screen flex justify-center items-center">
			<h2 class="relative z-10 text-7xl uppercase max-w-2xl text-center font-bold">we design with the future in mind.</h2>
		</div>
		<vue-particles class="absolute inset-0 -mt-10"
        color="#44403c"
        :particleOpacity="0.7"
        :particlesNumber="80"
        shapeType="circle"
        :particleSize="4"
        linesColor="#44403c"
        :linesWidth="1"
        :lineLinked="true"
        :lineOpacity="0.4"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
      >
      </vue-particles>
	</div>
	<div>asdasd</div>
</template>

<script>
import Layout from "../Shared/Layout";
// import VueParticles from 'vue-particles'
export default {
	layout: Layout
}
</script>

<script setup>
</script>

<style >
	body: {
		background-color: "red";
	}
</style>