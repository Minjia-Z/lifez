<script>
	let links = [""];
	import Demo from "$lib/demo.svelte";
	import Spacer from "$lib/utils/spacer.svelte";
</script>
<title>Birthdayz NFT Collection</title>
<div class="p-10 font-main min-h-screen ">
	<Demo />

	<Spacer height="10rem" />

	<div
		class="grid grid-cols-1 md:grid-cols-2 gap-10 items-center justify-items-center"
	>
		<img
			class="flex-1 object-cover md:order-last"
			src="/gift_nbg.png"
			alt="baloons"
		/>
		<div class="flex flex-col gap-8 justify-center max-w-md flex-1">
			<h1 class="text-5xl font-bold">The Collection</h1>
			<p id="test">
				The Birthdayz Coinz collection includes a total of 1,098 unique 
				coins made up of 3 different colours for each of the 366 
				days in a year. Each date is detailed with unique astronomical 
				features on the front and back side of the coin. 
				Making them truly special and meaningful.
			</p>
			<p>
				On top of the uniqueness and the exquisite design. Coin holders 
				will be able to access the interactive 
				contents in the near future, gain whitelist spots 
				for our next projects, airdrops, and participate 
				in our projects in various different ways. 

			</p>
			<div class="flex gap-4">
			</div>
		</div>
	</div>
</div>
