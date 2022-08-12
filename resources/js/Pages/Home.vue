<template>
	<div class="relative">
		<div class="h-screen flex justify-center items-center">
			<h2 class="relative -mt-36 z-10 text-7xl uppercase max-w-3xl text-center font-bold tracking-wider hover:scale-105 transition ease-in delay-100 font-poppins">we design with the future in mind.</h2>
		</div>
		<vue-particles class="absolute inset-0 -mt-10"
        color="#44403c"
        :particleOpacity="0.7"
        :particlesNumber="80"
        shapeType="triangle"
        :particleSize="5"
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
	<div class="relative bg-black text-white py-10">
		<div class="flex justify-center pt-7 ">
			<div class="space-y-2">
				<h2 class="text-3xl font-bold uppercase font-poppins">We Are STRATIX</h2>
				<hr class="w-1/2 mx-auto border-2 border-white">
			</div>
		</div>
		<div class="flex justify-center py-7">
			<div class="max-w-2xl z-10">
				<p class="tracking-wider text-center font-roboto">STRATIX is a design thinking agency with a multi-disciplinary approach to crafting winning solutions for clients. Whether you’re a large multinational brand or a high-growth startup, we’ll craft your ultimate, achievable,  strategy. From complete brand launches to smaller new features with repositioning,  if you can imagine it, we can create it for you.</p>
			</div>
			<div class="absolute xl:top-0 bottom-0 right-0 -z">
				<img class="h-32 hover:scale-95 transition ease-in delay-100" src="@/../assets/images/stratix_logo/STRATIX_LOGO_WHITE_ON_BLACK.svg">
			</div>
		</div>
	</div>
	<!-- partners -->
	<div class="bg-gray-50 py-16 flex justify-center">
		<div class="pt-7 px-36">
			<div class=" grid grid-cols-4 lg:grid-cols-8 justify-items-center items-center">
				<div>
					<img class="h-[96px]" src="@/../assets/images/stratix_clients/COKA_COLA.svg">
				</div>
				<div>
					<img class="h-[96px]" src="@/../assets/images/stratix_clients/DIAGEO.svg">
				</div>
				<div>
					<img class="h-[96px]" src="@/../assets/images/stratix_clients/SMIRNOFF.svg">
				</div>
				<div>
					<img class="h-[96px]" src="@/../assets/images/stratix_clients/ALX.svg">
				</div>
				<div>
					<img class="h-[96px]" src="@/../assets/images/stratix_clients/TEDx.svg">
				</div>
				<div>
					<img class="h-[96px]" src="@/../assets/images/stratix_clients/TOURISM_ETHIOPIA.svg">
				</div>
				<div>
					<img class="h-[96px]" src="@/../assets/images/stratix_clients/ALG.svg">
				</div>
				<div>
					<img class="h-[96px]" src="@/../assets/images/stratix_clients/KANA_TV.svg">
				</div>
			</div>
		</div>
	</div>

	<!-- what we do -->

	<div class="px-12 py-12">
		<div class="py-12 flex justify-center">
			<div class="max-w-3xl">
				<h2 class="text-center text-gray-700 text-2xl font-semibold uppercase tracking-wider font-poppins">CREATING WINNING SOLUTIONS WITH THE RELENTLESS PURSUIT OF INNOVATION.</h2>
			</div>
				
		</div>
		<div class="grid grid-cols-2 gap-8 shadow-xl p-8  bg-gray-50">
			<div class="p-7 shadow bg-white">
				<div class="p-4 space-y-4 hover:scale-105 transition ease-in delay-100">
					<p class="uppercase tracking-wider font-bold font-poppins">social media strategy</p>
					<hr class="w-1/6 border-black">
					<p class="p-4 text-sm tracking-wide text-gray-500 leading-6 font-roboto">We know the social media ecosystem incredibly well. You’ll benefit from this knowledge and experience as we help you come up with the perfect social media strategy and achieve your specific goals. Whether organic, paid, or both, we know how to create content that engages your users and inspires them to take action with your brand. Everything we do has quantifiable KPIs and is aimed to achieve one thing and one thing only: to get results. We send regular progress reports, including highlighting impressive numbers, areas of growth, and new opportunities.</p>
				</div>
			</div>

			<div class="p-7 shadow bg-white">
				<div class="p-4 space-y-4 hover:scale-105 transition ease-in delay-100">
					<p class="uppercase tracking-wider font-bold font-poppins">brand identity</p>
					<hr class="w-1/6 border-black">
					<p class="p-4 text-sm tracking-wide text-gray-500 leading-6 font-roboto">Brand identity is the true reflection that an organization portrays to its customers which includes the promise of the brand from the company to the customers assuring them of true value delivery. It is essentially a bridge built on trust and credibility between the company and the consumer.
					<br> In this accelerated world, people make decisions in the blink of an eye, through sensory means, without thinking about it logically. Brand design – sonic and visual – is not a “nice to have.” It’s essential to building modern, growth-driven brands.</p>
				</div>
			</div>

			<div class="p-7 shadow bg-white">
				<div class="p-4 space-y-4 hover:scale-105 transition ease-in delay-100">
					<p class="uppercase tracking-wider font-bold font-poppins">research & insight</p>
					<hr class="w-1/6 border-black">
					<p class="p-4 text-sm tracking-wide text-gray-500 leading-6 font-roboto">We use data to map behaviors and recognize patterns emerging in the world, both within the category and those that are specific to the business and the brand. With that knowledge, we uncover the most significant opportunities to maximize how and when people engage. Working with STRATIX will give you insights into evolving trends, media consumption habits, brands and market share insights.</p>
				</div>
			</div>

			<div class="p-7 shadow bg-white">
				<div class="p-4 space-y-4 hover:scale-105 transition ease-in delay-100">
					<p class="uppercase tracking-wider font-bold font-poppins">marketing video production</p>
					<hr class="w-1/6 border-black">
					<p class="p-4 text-sm tracking-wide text-gray-500 leading-6 font-roboto">Craft the perfect cross-platform campaigns, that work together throughout a user’s journey; from TV to social media. These campaigns consist of a series of different kinds of videos in multiple sizes, with differentiated messaging to suit distinct needs.</p>
				</div>
			</div>
		</div>
	</div>


	<!-- testimonials sction -->

	<div class="py-7 px-12">
		<div class="space-y-4">
			<div class="py-4">
				<!-- <h2 class="text-center text-2xl font-bold uppercase tracking-wider">Our clients love what we do</h2> -->
			</div>
			
			<div class="grid grid-cols-6 gap-4 place-items-center content-center">
				<div class="xl:col-span-3 col-span-6 flex items-center">
					<h2 class="max-w-3xl font-poppins text-center text-7xl font-bold tracking-wider">Our clients love what we do.</h2>
				</div>
				<div class="xl:col-span-3 col-span-6   shadow flex items-center bg-black text-white">
					<div class="shrink-0 pl-2">
						<img class="h-32 w-32 object-contain border rounded rounded-full w-auto" src="https://www.apple.com/leadership/images/bio/tim-cook_image.png.large.png">
					</div>
					<div class="p-4">
						<svg class="h-12 mb-3 text-gray-400 dark:text-gray-600" viewBox="0 0 24 27" fill="none" 	xmlns="http://www.w3.org/2000/svg">
		              		<path d="M14.017 18L14.017 10.609C14.017 4.905 17.748 1.039 23 0L23.995 2.151C21.563 3.068 20 5.789 20 8H24V18H14.017ZM0 18V10.609C0 4.905 3.748 1.038 9 0L9.996 2.151C7.563 3.068 6 5.789 6 8H9.983L9.983 18L0 18Z" fill="currentColor"/>
		          		</svg>
		          		<h1 class="text-2xl font-bold font-poppins">It was a greate experience !</h1>
		          		<div class="p-4 ml-2">
		          			<p class="shadow border-l-[1px] p-4 max-xl font-roboto text-gray-300 tracking-wide">STRATIX is a design thinking agency with a 	multi-disciplinary approach to crafting winning solutions for clients. Whether you’re a large multinational brand or a high-growth startup, we’ll craft your ultimate, achievable, strategy.</p>

		          			<div class=" py-8 space-x-2 font-bold font-roboto tracking-wide">
		          				<div class="flex justify-center items-center space-x-2">
		          					<p>Tim Cook</p>
		          					<hr class="w-[2px] h-6 border border-gray-400">
		          					<p>CEO at Apple</p>
		          				</div>
		          			</div>
		          		</div>
					</div>
				</div>
				<div class="xl:col-span-3 col-span-6  shadow-2xl flex items-center bg-black text-white">
					<div class="shrink-0">
						<img class="h-40" src="https://www.apple.com/leadership/images/bio/tim-cook_image.png.large.png">
					</div>
					<div class="p-4">
						<svg class="h-12 mb-3 text-gray-400 dark:text-gray-600" viewBox="0 0 24 27" fill="none" 	xmlns="http://www.w3.org/2000/svg">
		              		<path d="M14.017 18L14.017 10.609C14.017 4.905 17.748 1.039 23 0L23.995 2.151C21.563 3.068 20 5.789 20 8H24V18H14.017ZM0 18V10.609C0 4.905 3.748 1.038 9 0L9.996 2.151C7.563 3.068 6 5.789 6 8H9.983L9.983 18L0 18Z" fill="currentColor"/>
		          		</svg>
		          		<h1 class="text-2xl font-bold font-poppins">It was a greate experience !</h1>
		          		<div class="p-4 ml-2">
		          			<p class="border-l-[1px] p-4 max-w-3xl font-roboto text-gray-300 tracking-wide">STRATIX is a design thinking agency with a 	multi-disciplinary approach to crafting winning solutions for clients. Whether you’re a large multinational brand or a high-growth startup, we’ll craft your ultimate, achievable, strategy. From complete brand launches to smaller new features with repositioning, if you can imagine it, we can create it for you.</p>

		          			<div class=" py-8 space-x-2 font-bold font-roboto tracking-wide">
		          				<div class="flex justify-center items-center space-x-2">
		          					<p>Tim Cook</p>
		          					<hr class="w-[2px] h-6 border border-gray-400">
		          					<p>CEO at Apple</p>
		          				</div>
		          			</div>
		          		</div>
					</div>
				</div>
				<div class="xl:col-span-3 col-span-6 shadow flex items-center bg-gray-50 border">
					<div class="shrink-0">
						<img class="h-32 w-32 object-contain w-auto" src="https://www.apple.com/leadership/images/bio/tim-cook_image.png.large.png">
					</div>
					<div class="p-4">
						<svg class="h-12 mb-3 text-gray-700 dark:text-gray-600" viewBox="0 0 24 27" fill="none" 	xmlns="http://www.w3.org/2000/svg">
		              		<path d="M14.017 18L14.017 10.609C14.017 4.905 17.748 1.039 23 0L23.995 2.151C21.563 3.068 20 5.789 20 8H24V18H14.017ZM0 18V10.609C0 4.905 3.748 1.038 9 0L9.996 2.151C7.563 3.068 6 5.789 6 8H9.983L9.983 18L0 18Z" fill="currentColor"/>
		          		</svg>
		          		<h1 class="text-2xl font-bold font-poppins">It was a greate experience !</h1>
		          		<div class="p-4 ml-2">
		          			<p class="shadow border-l-[1px] p-4 max-w-3xl font-roboto text-gray-700 tracking-wide">STRATIX is a design thinking agency with a 	multi-disciplinary approach to crafting winning solutions for clients. Whether you’re a large multinational brand or a high-growth startup, we’ll craft your ultimate, achievable, strategy. From complete brand launches to smaller new features with repositioning, if you can imagine it, we can create it for you.</p>

		          			<div class="text-gray-900 py-8 space-x-2 font-bold font-roboto tracking-wide">
		          				<div class="flex justify-center items-center space-x-2">
		          					<p>Tim Cook</p>
		          					<hr class="w-[2px] h-6 border border-gray-400">
		          					<p>CEO at Apple</p>
		          				</div>
		          			</div>
		          		</div>
					</div>
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