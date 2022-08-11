<template>
	<div class="px-12">
		<div class="grid grid-cols-2 py-36 place-items-center px-24 shadow-sm">
			<div class="max-w-2xl">
				<p class="text-7xl font-extrabold ">Let's create progress together</p>
			</div>
			<!-- form -->
			<div class="">
				<form class="w-full max-w-lg">
				  <div class="flex flex-wrap -mx-3 mb-6">
				    <!-- <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
				      <label class="block uppercase tracking-wider text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
				        First Name
				      </label>
				      <input class="appearance-none block w-full text-gray-700 border border-red-500 py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" id="grid-first-name" type="text" placeholder="Paul">
				      <p class="text-red-500 text-xs italic">Please fill out this field.</p>
				    </div> -->
				    <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
				      <label class="block uppercase tracking-wider text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
				        First Name
				      </label>
				      <input class="appearance-none block w-full text-gray-700 border border-black py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" id="grid-first-name" type="text" placeholder="Paul">
				    </div>
				    <div class="w-full md:w-1/2 px-3">
				      <label class="block uppercase tracking-wider text-gray-700 text-xs font-bold mb-2" for="grid-last-name">
				        Last Name
				      </label>
				      <input class="appearance-none block w-full text-gray-700 border border-black py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="Tad">
				    </div>
				  </div>
				  <div class="flex flex-wrap -mx-3 mb-6">
				    <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
				      <label class="block uppercase tracking-wider text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
				        Email
				      </label>
				      <input class="appearance-none block w-full text-gray-700 border border-black py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" id="grid-first-name" type="email" placeholder="naz@gmail.com">
				    </div>
				    <div class="w-full md:w-1/2 px-3">
				      <label class="block uppercase tracking-wider text-gray-700 text-xs font-bold mb-2" for="grid-last-name">
				        Phone number
				      </label>
				      <input class="appearance-none block w-full text-gray-700 border border-black py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="+251-922744488">
				    </div>
				  </div>
				  <div class="flex flex-wrap -mx-3 mb-6">
				    <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
				      <label class="block uppercase tracking-wider text-gray-700 text-xs font-bold mb-2" for="grid-city">
				        City
				      </label>
				      <input class="appearance-none block w-full text-gray-700 border border-black py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-city" type="text" placeholder="Addis Ababa">
				    </div>
				    <!-- <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
				      <label class="block uppercase tracking-wider text-gray-700 text-xs font-bold mb-2" for="grid-state">
				        State
				      </label>
				      <div class="relative">
				        <select class="block appearance-none w-full border border-black text-gray-700 py-3 px-4 pr-8 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-state">
				          <option>New Mexico</option>
				          <option>Missouri</option>
				          <option>Texas</option>
				        </select>
				        <div class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-2 text-gray-700">
				          <svg class="fill-current h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M9.293 12.95l.707.707L15.657 8l-1.414-1.414L10 10.828 5.757 6.586 4.343 8z"/></svg>
				        </div>
				      </div>
				    </div> -->
				    <!-- <div class="w-full md:w-1/3 px-3 mb-6 md:mb-0">
				      <label class="block uppercase tracking-wider text-gray-700 text-xs font-bold mb-2" for="grid-zip">
				        Zip
				      </label>
				      <input class="appearance-none block w-full text-gray-700 border border-black py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-zip" type="text" placeholder="90210">
				    </div> -->
				  </div>
				  <div class="flex flex-wrap mb-2">
				  	<button class="bg-black text-white px-5 py-2 tracking-wider uppercase text-sm hover:scale-105 transition ease-in delay-100">subscribe</button>
				  </div>
				</form>
			</div>
		</div>
		<!-- map -->
		<div class="shadow-2xl p-4">
			<iframe class="w-full h-[450px] border p-4" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3940.6738893671045!2d38.77751981535902!3d9.002124593539545!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b85936109263f%3A0x78fb74bc4687be4c!2sThe%20Place%20luxury%20apartment!5e0!3m2!1sen!2set!4v1659184918008!5m2!1sen!2set"  allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
		</div>
	</div>
</template>

<script>
import Layout from "../Shared/Layout";
export default {
	layout: Layout
}
</script>

<script setup>
</script>

<style lang="css" scoped>
</style>