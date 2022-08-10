<template>
	<div class="relative">
		<div class="h-screen flex justify-center items-center">
			<h2 class="relative z-10 text-7xl uppercase max-w-2xl text-center font-bold tracking-wide first-letter:text-9xl hover:scale-105 transition ease-in delay-100">we design with the future in mind.</h2>
		</div>
		<vue-particles class="absolute inset-0 -mt-10"
        color="#44403c"
        :particleOpacity="0.7"
        :particlesNumber="80"
        shapeType="triangle"
        :particleSize="4"
        linesColor="#44403c"
        :linesWidth="1"
        :lineLinked="true"
        :lineOpacity="0.7"
        :linesDistance="150"
        :moveSpeed="3"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="true"
        clickMode="push"
      >
      </vue-particles>
	</div>

	<!-- who we are ? -->
	<div class="bg-black text-white py-10">
		<div class="flex justify-center pt-7">
			<div class="space-y-2">
				<h2 class="text-3xl font-bold uppercase">We Are STRATIX</h2>
				<hr class="w-1/2 mx-auto border-2 border-white">
			</div>
		</div>
		<div class="flex justify-center py-7">
			<div class="max-w-2xl">
				<p class="first-letter:text-3xl">We design and develop digital products and online experiences that help our clients grow, innovate, and transform. We listen, learn and understand before we build. We identify your goals together, then use our expertise to find that sweet spot of realistic and impactful.</p>
			</div>
		</div>
	</div>
	<!-- partners -->
	<div class="bg-gray-100 py-16 flex justify-center">
		<div class="pt-7 px-36">
			<div class=" grid grid-cols-7 justify-items-center items-center">
				<div>
					<img class="h-[39px]" src="https://laravel.com/images/companies/disney.png">
				</div>
				<div>
					<img class="h-[24px]" src="https://laravel.com/images/companies/bankrate.png">
				</div>
				<div>
					<img class="h-[37px]" src="https://laravel.com/images/companies/warner-bros.png">
				</div>
				<div>
					<img class="h-[31px]" src="https://laravel.com/images/companies/the-new-york-times.png">
				</div>
				<div>
					<img class="h-[42px]" src="https://laravel.com/images/companies/wwe.png">
				</div>
				<div>
					<img class="h-[32px]" src="https://laravel.com/images/companies/twitch.png">
				</div>
				<div>
					<img class="h-[28px]" src="https://laravel.com/images/companies/about-you.png">
				</div>
			</div>
		</div>
	</div>

	<!-- another sction -->

	<div class="py-7 px-12">
		<div class="space-y-4">
			<div class="flex space-x-2">
				<div>
					<img class="hover:scale-105 transition ease-in delay-100" src="https://media.istockphoto.com/photos/side-portrait-of-african-american-man-staring-picture-id935110490?k=20&m=935110490&s=612x612&w=0&h=mB-pKUFbT3Vl4ArAi0LDr-W8y647-nxMVeHyPadYb60=">
				</div>
				<div class="bg-gray-50 flex items-center max-w-sm hover:scale-105 transition ease-in delay-100 shadow-lg">
					<div class="p-4 space-y-4">
						<p class="font-bold text-gray-400 uppercase">the modern monolith</p>
						<p class="font-bold text-2xl">Powerd By InertiaJS</p>
						<hr class="w-1/2" />
						<p class="text-gray-400 text-sm tracking-wide">Inertia allows you to create fully client-side rendered, single-page apps, without much of the complexity that comes with modern SPAs. It does this by leveraging existing server-side frameworks.</p>
					</div>
				</div>
				<div class="flex items-center justify-center flex-1 uppercase tracking-wider">
					<button class="flex space-x-4 border border-2 border-black p-4 hover:scale-105 transition ease-in delay-100">	
						<p class="text-sm tracking-wider">See Details</p>
						<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
						  <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
						</svg>
					</button>
				</div>
			</div>

			<div class="flex flex-row-reverse space-x-2">
				<div>
					<img class="hover:scale-105 transition ease-in delay-100" src="https://media.istockphoto.com/photos/beautiful-girl-with-curly-hairstyle-picture-id1292414100?k=20&m=1292414100&s=612x612&w=0&h=LXZWODEJuL9K19hG2RPUZZnXFJTG3CBj-RT0HV9lZiw=">
				</div>
				<div class="bg-gray-50 flex items-center max-w-sm hover:scale-105 transition ease-in delay-100 shadow-lg">
					<div class="p-4 space-y-4">
						<p class="font-bold text-2xl">Powerd By VueJS</p>
						<hr class="w-1/2" />
						<p class="text-gray-400 text-sm tracking-wide">Inertia allows you to create fully client-side rendered, single-page apps, without much of the complexity that comes with modern SPAs. It does this by leveraging existing server-side frameworks.</p>
					</div>
				</div>
				<div class="flex items-center justify-center flex-1 uppercase tracking-wider">
					<button class="flex space-x-4 border border-2 border-black p-4 hover:scale-105 transition ease-in delay-100">	
						<p class="text-sm tracking-wider">See Details</p>
						<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
						  <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
						</svg>
					</button>
				</div>
			</div>

			<div class="flex space-x-2">
				<div>
					<img class="hover:scale-105 transition ease-in delay-100" src="https://media.istockphoto.com/photos/white-desktop-mockup-workplace-conceptual-image-picture-id1271672909?k=20&m=1271672909&s=612x612&w=0&h=jzzw78bZahpkfqObnGtfhQhpi6RCNQP2EvowI6tndrE=">
				</div>
				<div class="bg-gray-50 flex items-center max-w-sm hover:scale-105 transition ease-in delay-100 shadow-lg">
					<div class="p-4 space-y-4">
						<div>
							<p class="text-sm">The PHP Framework</p>
							<p class="font-bold text-gray-400">For Web Artisans</p>
						</div>
						<p class="font-bold text-2xl">Laravel is an awesome framework</p>
						<hr class="w-1/2" />
						<p class="text-gray-400 text-sm tracking-wide">Laravel is a web application framework with expressive, elegant syntax. We’ve already laid the foundation — freeing you to create without sweating the small things.</p>
					</div>
				</div>
				<div class="flex items-center justify-center flex-1 uppercase tracking-wider">
					<button class="flex space-x-4 border border-2 border-black p-4 hover:scale-105 transition ease-in delay-100">	
						<p class="text-sm tracking-wider">See Details</p>
						<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
						  <path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3" />
						</svg>
					</button>
				</div>
			</div>

		</div>
	</div>

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