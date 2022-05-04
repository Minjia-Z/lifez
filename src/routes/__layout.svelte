<script>
    import Footer from "$lib/footer.svelte";
    import Spacer from "$lib/utils/spacer.svelte";
    import "../app.css";
</script>

<div class="max-w-screen-lg mx-auto">
    <div class="navbar bg-base-100 my-10">
        <div class="flex-1">
            <a class="flex normal-case text-xl" href="/"
                ><img class="h-10" src="/LIFEZ_logo.jpg" alt="logo" /></a
            >
        </div>
        <div class="flex-none">
            <ul class="menu menu-horizontal p-0">
                <li><a>Purchase Now</a></li>
                <li><a href="#demoParagraph">Roadmap</a></li>
                <li><a href="#footer">About Us</a></li>
                <li tabindex="0">
                    <a>
                        Connect with Us
                        <svg
                            class="fill-current"
                            xmlns="http://www.w3.org/2000/svg"
                            width="20"
                            height="20"
                            viewBox="0 0 24 24"
                        >
                            <path
                                d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z"
                            />
                        </svg>
                    </a>
                    <ul class="p-2 bg-base-100">
                        <li><a href="https://twitter.com/LifeZ_NFT" target="_blank">Twitter</a></li>
                        <li><a href="https://www.instagram.com/lifez_nft/" target="_blank">Instagram</a></li>
                        <li><a href="https://discord.com/invite/AwaRjxDZDw" target="_blank">Discord</a></li>
                    </ul>
                </li>
            </ul>
        </div>
    </div>

    <slot />
    <Spacer />
    <Footer />
</div>
