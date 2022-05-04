<script>
    import Countdown from "./countdown.svelte";
    import Spacer from "$lib/utils/spacer.svelte";
</script>

<div
    class="grid grid-cols-1 md:grid-cols-2 gap-x-10 gap-y-0 items-center justify-items-center"
>
    <img class="object-cover" src="/coin_may15.gif" alt="baloons" />
    <div class="flex flex-col gap-8 justify-center max-w-md items-center">
        <h1 class="text-5xl font-bold">Birthdayz Coin</h1>
        <p id="demoParagraph" class="text-lg" >
            Introducing a first-in-class collection design in the entire NFT space! 
            Celebrate lifez of you and your loved ones by adding this NFT to your collection! 
        </p>
        <Spacer height="0rem" />
        <Countdown />
        <div class="flex gap-4">
            <button class="btn btn-lg btn-primary rounded-full"
                >coming soon</button
            >
        </div>
    </div>
</div>
