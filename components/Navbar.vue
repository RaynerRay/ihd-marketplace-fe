<template>
<div class="app-header">

    <!-- Navbar component -->
		<nav class="bg-custombg shadow-sm">
			<div class="max-w-6xl mx-auto px-4">
				<div class="flex justify-between">
					<div class="flex space-x-7">
						<div>
							<!-- Website Logo -->
							<a href="#" class="flex items-center py-4 px-2">
								<img src="/ihd-2.png" alt="Logo" class="h-8 w-16 mr-2">
								<span class="font-semibold text-gray-500 text-lg">IHD</span>
							</a>
						</div>
						<!-- Primary Navbar items -->
						<div class="hidden md:flex items-center space-x-1">
							<a href="" class="py-4 px-2 text-red-600 border-b-4 border-red-600 font-semibold ">Home</a>
							<a href="" class="py-4 px-2 text-gray-500 font-semibold hover:text-red-600 transition duration-300">Services</a>
							<a href="" class="py-4 px-2 text-gray-500 font-semibold hover:text-red-600 transition duration-300">About</a>
							<a href="" class="py-4 px-2 text-gray-500 font-semibold hover:text-red-600 transition duration-300">Contact Us</a>
						</div>
					</div>
					<!-- Secondary Navbar items -->
					<div class="hidden md:flex items-center space-x-3 ">
						<a href="" class="py-2 px-2 font-medium text-gray-500 rounded hover:bg-red-600 hover:text-white transition duration-300">Log In</a>
						<nuxt-link to="/registration/register" class="py-2 px-2 font-medium text-white
						 bg-gray-600 rounded hover:bg-red-600 transition duration-300">Register</nuxt-link>
					</div>
					<!-- Mobile menu button -->
					<div class="md:hidden flex items-center">
						<button class="outline-none mobile-menu-button"  
 						@click="showMobileMenu = !showMobileMenu">
						<svg class=" w-6 h-6 text-gray-500 hover:text-red-600 "
							x-show="!showMenu"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path d="M4 6h16M4 12h16M4 18h16"></path>
						</svg>
					</button>
					</div>
				</div>
			</div>
			<!-- mobile menu -->
			<div v-show="!showMobileMenu">
				<ul class="">
					<li class="active"><a href="index.html" class="block text-sm px-2 py-4 text-white bg-red-600 font-semibold">Home</a></li>
					<li><a href="#services" class="block text-sm px-2 py-4 hover:bg-red-600 transition duration-300">Services</a></li>
					<li><a href="#about" class="block text-sm px-2 py-4 hover:bg-red-600 transition duration-300">About</a></li>
					<li><a href="#contact" class="block text-sm px-2 py-4 hover:bg-red-600 transition duration-300">Contact Us</a></li>
				</ul>
			</div>
        </nav>
    
</div>

 </template>   
 
 <script>
 export default {
  name: 'Navbar',
  data () {
    return {
      showMobileMenu: true
    }
  },
 methods: {
    showMobileMenu () {
      this.$emit('showMobileMenu')
    }
  }
};
</script>