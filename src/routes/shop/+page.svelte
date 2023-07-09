<!-- breadcrums -->
<div class="container py-4 flex items-center gap-3 pt-52">
	<a href="/" class="text-primary text-base">
		<i class="fas fa-home" />
	</a>
	<span class="text-sm text-gray-400">
		<i class="fas fa-chevron-right" />
	</span>
	<p class="text-gray-600 font-medium">Shop</p>
</div>

<!-- shop wrapper -->
<div class="container md:grid md:grid-cols-4 gap-6 pt-4 pb-16 items-start">
	<!-- sidebar -->
	<div class="col-span-1 bg-white px-4 pb-6 shadow rounded overflow-hidden">
		<div class="divide-y divide-gray-200 space-y-5">
			<!-- category filter -->
			<div class="pt-4">
				<h3 class="text-xl text-gray-800 mb-3 uppercase font-medium">categories</h3>
				<div class="space-y-2">
					<!-- single category -->
					<div class="flex items-center">
						<input type="checkbox" id="cat-1" />
						<label for="cat-1" class="text-gray-600 ml-3 cursor-pointer">Bedroom</label>
						<div class="ml-auto text-gray-600 text-sm">(15)</div>
					</div>
					<div class="flex items-center">
						<input type="checkbox" id="cat-1" />
						<label for="cat-1" class="text-gray-600 ml-3 cursor-pointer">Bathroom</label>
						<div class="ml-auto text-gray-600 text-sm">(12)</div>
					</div>
					<div class="flex items-center">
						<input type="checkbox" id="cat-1" />
						<label for="cat-1" class="text-gray-600 ml-3 cursor-pointer">Kitchenroom</label>
						<div class="ml-auto text-gray-600 text-sm">(09)</div>
					</div>
					<div class="flex items-center">
						<input type="checkbox" id="cat-1" />
						<label for="cat-1" class="text-gray-600 ml-3 cursor-pointer">Diningroom</label>
						<div class="ml-auto text-gray-600 text-sm">(06)</div>
					</div>
				</div>
			</div>

			<!-- category filter -->
			<div class="pt-4">
				<h3 class="text-xl text-gray-800 mb-3 uppercase font-medium">brands</h3>
				<div class="space-y-2">
					<!-- single category -->
					<div class="flex items-center">
						<input type="checkbox" id="cat-1" />
						<label for="cat-1" class="text-gray-600 ml-3 cursor-pointer">Dominik</label>
						<div class="ml-auto text-gray-600 text-sm">(15)</div>
					</div>
					<div class="flex items-center">
						<input type="checkbox" id="cat-1" />
						<label for="cat-1" class="text-gray-600 ml-3 cursor-pointer">Karl</label>
						<div class="ml-auto text-gray-600 text-sm">(18)</div>
					</div>
					<div class="flex items-center">
						<input type="checkbox" id="cat-1" />
						<label for="cat-1" class="text-gray-600 ml-3 cursor-pointer">Maxing</label>
						<div class="ml-auto text-gray-600 text-sm">(09)</div>
					</div>
					<div class="flex items-center">
						<input type="checkbox" id="cat-1" />
						<label for="cat-1" class="text-gray-600 ml-3 cursor-pointer">Ernest</label>
						<div class="ml-auto text-gray-600 text-sm">(12)</div>
					</div>
				</div>
			</div>

			<!-- price filter -->
			<div class="pt-4">
				<h3 class="text-xl text-gray-800 mb-3 uppercase font-medium">price</h3>
				<div class="mt-4 flex items-center">
					<input
						type="text"
						class="w-full border-gray-300 focus:border-primary focus:ring-0 px-3 py-1 text-gray-600 text-sm shadow-sm rounded"
						placeholder="min"
					/>
					<span class="mx-3 text-gray-500">-</span>
					<input
						type="text"
						class="w-full border-gray-300 focus:border-primary focus:ring-0 px-3 py-1 text-gray-600 text-sm shadow-sm rounded"
						placeholder="max"
					/>
				</div>
			</div>

			<!-- size filter -->
			<div class="pt-4">
				<h3 class="text-xl text-gray-800 mb-3 uppercase font-medium">size</h3>
				<div class="flex items-center gap-2">
					<!-- single size -->
					<div class="size-selector">
						<input type="radio" name="size" class="hidden" id="size-xs" />
						<label
							for="size-xs"
							class="text-xs border border-gray-200 rounded-sm h-6 w-6 flex items-center justify-center cursor-pointer shadow-sm text-gray-600"
							>XS</label
						>
					</div>
					<div class="size-selector">
						<input type="radio" name="size" class="hidden" id="size-s" />
						<label
							for="size-s"
							class="text-xs border border-gray-200 rounded-sm h-6 w-6 flex items-center justify-center cursor-pointer shadow-sm text-gray-600"
							>S</label
						>
					</div>
					<div class="size-selector">
						<input type="radio" name="size" class="hidden" id="size-m" />
						<label
							for="size-m"
							class="text-xs border border-gray-200 rounded-sm h-6 w-6 flex items-center justify-center cursor-pointer shadow-sm text-gray-600"
							>M</label
						>
					</div>
					<div class="size-selector">
						<input type="radio" name="size" class="hidden" id="size-l" />
						<label
							for="size-l"
							class="text-xs border border-gray-200 rounded-sm h-6 w-6 flex items-center justify-center cursor-pointer shadow-sm text-gray-600"
							>L</label
						>
					</div>
					<div class="size-selector">
						<input type="radio" name="size" class="hidden" id="size-xl" />
						<label
							for="size-xl"
							class="text-xs border border-gray-200 rounded-sm h-6 w-6 flex items-center justify-center cursor-pointer shadow-sm text-gray-600"
							>XL</label
						>
					</div>
				</div>
			</div>

			<!-- color filter -->
			<div class="pt-4">
				<h3 class="text-xl text-gray-800 mb-3 uppercase font-medium">color</h3>
				<div class="flex items-center gap-2">
					<!-- single color -->
					<div class="color-selector">
						<input type="radio" name="color" class="hidden" id="color-red" />
						<label
							for="color-red"
							class="border border-gray-200 rounded-sm h-5 w-5 cursor-pointer shadow-sm block"
							style="background-color: #fc3d57;"
						/>
					</div>
					<div class="color-selector">
						<input type="radio" name="color" class="hidden" id="color-purple" />
						<label
							for="color-purple"
							class="border border-gray-200 rounded-sm h-5 w-5 cursor-pointer shadow-sm block"
							style="background-color: #c0c;"
						/>
					</div>
					<div class="color-selector">
						<input type="radio" name="color" class="hidden" id="color-black" />
						<label
							for="color-black"
							class="border border-gray-200 rounded-sm h-5 w-5 cursor-pointer shadow-sm block"
							style="background-color: #000;"
						/>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!-- product -->
	<div class="col-span-3 mt-20 md:mt-0">
		<!-- sorting -->
		<div class="flex items-center mb-4">
			<select
				class="w-44 text-sm cursor-pointer text-gray-600 px-4 py-3 border-gray-300 shadow-sm rounded focus:ring-primary focus:border-primary"
			>
				<option>Default sorting</option>
				<option>Price low-hight</option>
				<option>Price hight-low</option>
				<option>Latest product</option>
			</select>

			<div class="flex gap-2 ml-auto">
				<div
					class="border border-primary w-10 h-9 flex items-center justify-center text-white bg-primary rounded cursor-pointer"
				>
					<i class="fas fa-th" />
				</div>
				<div
					class="border border-gray-400 w-10 h-9 flex items-center justify-center text-gray-600 rounded cursor-pointer"
				>
					<i class="fas fa-list" />
				</div>
			</div>
		</div>

		<!-- product grid -->
		<div class="grid grid-cols-2 md:grid-cols-3 gap-4 lg:gap-6">
			<!-- product 1 -->
			<div class="bg-white rounded shadow overflow-hidden group">
				<!-- product image -->
				<div class="relative">
					<img src="assets/product5.png" alt="product1" class="w-full" />
					<div
						class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center gap-2 opacity-0 group-hover:opacity-100 transition"
					>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="fas fa-search" />
						</a>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="far fa-heart" />
						</a>
					</div>
				</div>
				<!-- product content -->
				<div class="pt-4 pb-3 px-4">
					<a href="/">
						<h4
							class="font-medium text-lg md:text-xl mb-2 text-gray-800 hover:text-primary transition"
						>
							Giomarr
						</h4>
					</a>
					<div class="flex items-baseline mb-1 space-x-2 font-roboto">
						<p class="text-lg md:text-xl text-primary font-semibold">$45.00</p>
						<p class="text-lg md:text-xl text-gray-400 line-through">$55.00</p>
					</div>
					<div class="flex items-center">
						<div class="flex gap-1 text-xs md:text-sm text-yellow-400">
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
						</div>
						<div class="text-xs text-gray-500 ml-3">(150)</div>
					</div>
				</div>
				<a
					href="/"
					class="block w-full py-1 text-center text-white bg-primary border border-primary rounded-b hover:bg-transparent hover:text-primary transition"
					>Add to cart</a
				>
			</div>
			<!-- product 2 -->
			<div class="bg-white rounded shadow overflow-hidden group">
				<!-- product image -->
				<div class="relative">
					<img src="assets/product6.png" alt="product2" class="w-full" />
					<div
						class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center gap-2 opacity-0 group-hover:opacity-100 transition"
					>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="fas fa-search" />
						</a>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="far fa-heart" />
						</a>
					</div>
				</div>
				<!-- product content -->
				<div class="pt-4 pb-3 px-4">
					<a href="/">
						<h4
							class="font-medium text-lg md:text-xl mb-2 text-gray-800 hover:text-primary transition"
						>
							Table
						</h4>
					</a>
					<div class="flex items-baseline mb-1 space-x-2 font-roboto">
						<p class="text-lg md:text-xl text-primary font-semibold">$45.00</p>
						<p class="text-lg md:text-xl text-gray-400 line-through">$55.00</p>
					</div>
					<div class="flex items-center">
						<div class="flex gap-1 text-xs md:text-sm text-yellow-400">
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
						</div>
						<div class="text-xs text-gray-500 ml-3">(150)</div>
					</div>
				</div>
				<a
					href="/"
					class="block w-full py-1 text-center text-white bg-primary border border-primary rounded-b hover:bg-transparent hover:text-primary transition"
					>Add to cart</a
				>
			</div>
			<!-- product 3 -->
			<div class="bg-white rounded shadow overflow-hidden group">
				<!-- product image -->
				<div class="relative">
					<img src="assets/product7.png" alt="product3" class="w-full" />
					<div
						class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center gap-2 opacity-0 group-hover:opacity-100 transition"
					>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="fas fa-search" />
						</a>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="far fa-heart" />
						</a>
					</div>
				</div>
				<!-- product content -->
				<div class="pt-4 pb-3 px-4">
					<a href="/">
						<h4
							class="font-medium text-lg md:text-xl mb-2 text-gray-800 hover:text-primary transition"
						>
							Table
						</h4>
					</a>
					<div class="flex items-baseline mb-1 space-x-2 font-roboto">
						<p class="text-lg md:text-xl text-primary font-semibold">$45.00</p>
						<p class="text-lg md:text-xl text-gray-400 line-through">$55.00</p>
					</div>
					<div class="flex items-center">
						<div class="flex gap-1 text-xs md:text-sm text-yellow-400">
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
						</div>
						<div class="text-xs text-gray-500 ml-3">(150)</div>
					</div>
				</div>
				<a
					href="/"
					class="block w-full py-1 text-center text-white bg-primary border border-primary rounded-b hover:bg-transparent hover:text-primary transition"
					>Add to cart</a
				>
			</div>
			<!-- product 4 -->
			<div class="bg-white rounded shadow overflow-hidden group">
				<!-- product image -->
				<div class="relative">
					<img src="assets/product8.png" alt="product4" class="w-full" />
					<div
						class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center gap-2 opacity-0 group-hover:opacity-100 transition"
					>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="fas fa-search" />
						</a>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="far fa-heart" />
						</a>
					</div>
				</div>
				<!-- product content -->
				<div class="pt-4 pb-3 px-4">
					<a href="/">
						<h4
							class="font-medium text-lg md:text-xl mb-2 text-gray-800 hover:text-primary transition"
						>
							Pot
						</h4>
					</a>
					<div class="flex items-baseline mb-1 space-x-2 font-roboto">
						<p class="text-lg md:text-xl text-primary font-semibold">$45.00</p>
						<p class="text-lg md:text-xl text-gray-400 line-through">$55.00</p>
					</div>
					<div class="flex items-center">
						<div class="flex gap-1 text-xs md:text-sm text-yellow-400">
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
						</div>
						<div class="text-xs text-gray-500 ml-3">(150)</div>
					</div>
				</div>
				<a
					href="/"
					class="block w-full py-1 text-center text-white bg-primary border border-primary rounded-b hover:bg-transparent hover:text-primary transition"
					>Add to cart</a
				>
			</div>
			<!-- product 5 -->
			<div class="bg-white rounded shadow overflow-hidden group">
				<!-- product image -->
				<div class="relative">
					<img src="assets/product9.png" alt="product5" class="w-full" />
					<div
						class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center gap-2 opacity-0 group-hover:opacity-100 transition"
					>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="fas fa-search" />
						</a>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="far fa-heart" />
						</a>
					</div>
				</div>
				<!-- product content -->
				<div class="pt-4 pb-3 px-4">
					<a href="/">
						<h4
							class="font-medium text-lg md:text-xl mb-2 text-gray-800 hover:text-primary transition"
						>
							Chair
						</h4>
					</a>
					<div class="flex items-baseline mb-1 space-x-2 font-roboto">
						<p class="text-lg md:selection:text-xl text-primary font-semibold">$45.00</p>
						<p class="text-lg md:selection:text-xl text-gray-400 line-through">$55.00</p>
					</div>
					<div class="flex items-center">
						<div class="flex gap-1 text-xs md:text-sm text-yellow-400">
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
						</div>
						<div class="text-xs text-gray-500 ml-3">(150)</div>
					</div>
				</div>
				<a
					href="/"
					class="block w-full py-1 text-center text-white bg-primary border border-primary rounded-b hover:bg-transparent hover:text-primary transition"
					>Add to cart</a
				>
			</div>
			<!-- product 6 -->
			<div class="bg-white rounded shadow overflow-hidden group">
				<!-- product image -->
				<div class="relative">
					<img src="assets/product10.png" alt="product6" class="w-full" />
					<div
						class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center gap-2 opacity-0 group-hover:opacity-100 transition"
					>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="fas fa-search" />
						</a>
						<a
							href="/"
							class="text-white text-lg w-9 h-8 rounded-full bg-primary flex items-center justify-center hover:bg-gray-800 transition"
						>
							<i class="far fa-heart" />
						</a>
					</div>
				</div>
				<!-- product content -->
				<div class="pt-4 pb-3 px-4">
					<a href="/">
						<h4
							class="font-medium text-lg md:text-xl mb-2 text-gray-800 hover:text-primary transition"
						>
							Corazon
						</h4>
					</a>
					<div class="flex items-baseline mb-1 space-x-2 font-roboto">
						<p class="text-lg md:text-xl text-primary font-semibold">$45.00</p>
						<p class="text-lg md:text-xl text-gray-400 line-through">$55.00</p>
					</div>
					<div class="flex items-center">
						<div class="flex gap-1 text-xs md:text-sm text-yellow-400">
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
							<span><i class="fas fa-star" /></span>
						</div>
						<div class="text-xs text-gray-500 ml-3">(150)</div>
					</div>
				</div>
				<a
					href="/"
					class="block w-full py-1 text-center text-white bg-primary border border-primary rounded-b hover:bg-transparent hover:text-primary transition"
					>Add to cart</a
				>
			</div>
		</div>
	</div>
</div>
