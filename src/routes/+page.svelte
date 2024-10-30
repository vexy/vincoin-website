<script>
    import { goto } from "$app/navigation";

    async function discordNavigation() {
        window.location.href = "https://discord.gg/dzbsT8jTg5";
    }
</script>

<section>
    <img src="/favicon.png" height="100" alt="vincoin_logo"/>
    <h1>VINCOIN</h1>
    <i>Modern currency for advanced mindset</i>

    <div>
        <button on:click|self={() => goto("/learn-more")}>Learn More</button>
        <button on:click|self={() => discordNavigation()} >
            <img src="/discord-mark-blue.svg" alt="discord_logo" height="20"/>
            <span>Join our Discord</span>
        </button>
    </div>
</section>

<style>
    section {
        height: 100vh;
        margin: 0;

        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    h1 {
        font-size: 3rem;
        text-align: center;
        margin: 10px;
    }

    img {
        border-radius: 15px;
    }

    i {
        margin: 10px;
    }

    div {
        display: flex;
        justify-content: center;
        gap: 15px;
    }

    button {
        border: none;
        border-radius: 10px;
        padding: 0.65rem;
        margin: 10px;

        display: flex;
        align-items: center;
        gap: 5px;

        font-family: "Overpass", sans-serif;
        font-optical-sizing: auto;
    }

    button:hover {
        font-style: italic;
        font-weight: 300;
        color: rgb(0, 119, 79);
    }
</style>