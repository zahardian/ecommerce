<script>
	import { slide } from 'svelte/transition';

	let show = false;
</script>

<div class="fixed z-50 w-full">
	<!-- header -->
	<header class="py-4 shadow-sm bg-white">
		<div class="container flex items-center justify-between">
			<a href="/" class="text-xl font-bold">
				<h1>Zaza<span class="text-primary">terior</span></h1>
			</a>

			<div class="w-full max-w-xl relative lg:flex hidden">
				<span class="absolute left-4 top-3 text-lg text-gray-400">
					<i class="fas fa-search" />
				</span>
				<input
					type="text"
					class="w-full border border-primary border-r-0 pl-12 py-3 pr-3 rounded-l-md focus:outline-none"
					placeholder="search"
				/>
				<button
					class="bg-primary border border-primary text-white px-8 rounded-r-md hover:bg-transparent hover:text-primary transition"
					>Search</button
				>
			</div>

			<div class="flex items-center space-x-4">
				<a href="/" class="text-center text-gray-700 hover:text-primary transition relative">
					<div class="text-lg md:text-2xl">
						<i class="far fa-heart" />
					</div>
					<div class="text-xs leading-3">Wish List</div>
					<span
						class="absolute right-0 -top-1 w-5 h-5 rounded-full flex items-center justify-center bg-primary text-white text-xs"
						>8</span
					>
				</a>
				<a href="/" class="text-center text-gray-700 hover:text-primary transition relative">
					<div class="text-lg md:text-2xl">
						<i class="fas fa-shopping-bag" />
					</div>
					<div class="text-xs leading-3">Cart</div>
					<span
						class="absolute right-0 -top-1 w-5 h-5 rounded-full flex items-center justify-center bg-primary text-white text-xs"
						>8</span
					>
				</a>
				<a href="/" class="text-center text-gray-700 hover:text-primary transition relative">
					<div class="text-lg md:text-2xl">
						<i class="far fa-user" />
					</div>
					<div class="text-xs leading-3">Account</div>
				</a>
			</div>
		</div>
	</header>

	<!-- navbar -->
	<nav class="bg-gray-800 py-4">
		<div class="container flex justify-between">
			<!-- all category -->
			<div
				class="px-3 py-2 md:px-5 md:py-4 bg-primary flex items-center cursor-pointer relative group"
			>
				<span class="text-white">
					<i class="fas fa-bars" />
				</span>
				<span class="capitalize ml-2 text-white">All Categories</span>
				<div
					class="absolute w-full left-0 top-full bg-white shadow-md py-3 divide-y divide-gray-300 divide-dashed opacity-0 group-hover:opacity-100 transition duration-500 invisible group-hover:visible"
				>
					<a href="/" class="flex items-center px-6 py-3 hover:bg-gray-100 transition">
						<img src="assets/sofa.svg" alt="sofa" class="w-5 h-5 object-contain" />
						<span class="ml-6 text-gray-600 text-sm">Sofa</span>
					</a>
					<a href="/" class="flex items-center px-6 py-3 hover:bg-gray-100 transition">
						<img src="assets/bed.svg" alt="bedroom" class="w-5 h-5 object-contain" />
						<span class="ml-6 text-gray-600 text-sm">Bedroom</span>
					</a>
					<a href="/" class="flex items-center px-6 py-3 hover:bg-gray-100 transition">
						<img src="assets/office.svg" alt="office" class="w-5 h-5 object-contain" />
						<span class="ml-6 text-gray-600 text-sm">Office</span>
					</a>
					<a href="/" class="flex items-center px-6 py-3 hover:bg-gray-100 transition">
						<img src="assets/outdoor-cafe.svg" alt="outdoor" class="w-5 h-5 object-contain" />
						<span class="ml-6 text-gray-600 text-sm">Outdoor</span>
					</a>
					<a href="/" class="flex items-center px-6 py-3 hover:bg-gray-100 transition">
						<img src="assets/bed-2.svg" alt="mattress" class="w-5 h-5 object-contain" />
						<span class="ml-6 text-gray-600 text-sm">Mattress</span>
					</a>
				</div>
			</div>

			<!-- navbar links -->
			<div class="lg:flex items-center justify-between flex-grow pl-12 hidden">
				<div class="flex items-center space-x-6 capitalize">
					<a href="/" class="text-gray-200 hover:text-white transition">Home</a>
					<a href="/shop" class="text-gray-200 hover:text-white transition">Shop</a>
					<a href="/about" class="text-gray-200 hover:text-white transition">About Us</a>
					<a href="/contact" class="text-gray-200 hover:text-white transition">Contact Us</a>
				</div>
				<a href="/login" class="text-gray-200 hover:text-white transition">Login/Register</a>
			</div>
			<button on:click={() => (show = !show)} class="text-white lg:hidden text-xl">
				<i class="fa-solid fa-bars" />
			</button>
		</div>
		{#if show}
			<div transition:slide>
				<div class="flex flex-col gap-4 py-2 pt-8 text-center capitalize">
					<a href="/" class="text-gray-200 hover:text-white transition">Home</a>
					<a href="/shop" class="text-gray-200 hover:text-white transition">Shop</a>
					<a href="/about" class="text-gray-200 hover:text-white transition">About Us</a>
					<a href="/contact" class="text-gray-200 hover:text-white transition">Contact Us</a>
					<a href="/login" class="text-gray-200 hover:text-white transition">Login/Register</a>
				</div>
			</div>
		{/if}
	</nav>
</div>
