<script>
    import Countdown from "./countdown.svelte";
</script>

<div
    class="grid grid-cols-1 md:grid-cols-2 gap-x-10 gap-y-0 items-center justify-items-center"
>
    <img class="object-cover" src="/coin_may15.gif" alt="baloons" />
    <div class="flex flex-col gap-8 justify-center max-w-md items-center">
        <h1 class="text-5xl font-bold">Birthdayz Coin</h1>
        <p id="demoParagraph">
            A first-in-class collection design in the entire NFT space. The
            Birthdayz Coin collection includes a total of 1,098 unique coins
            made up of 3 different styles for each day in the year.
        </p>
        <p>
            Coin holders will be able to access the interactive contents in the
            near future, gain whitelist spots for our next projects, airdrops,
            and participate in our projects in various different ways.
        </p>
        <Countdown />
        <div class="flex gap-4">
            <button class="btn btn-lg btn-primary rounded-full"
                >coming soon</button
            >
        </div>
    </div>
</div>
