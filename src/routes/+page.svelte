<script>
    import { goto } from "$app/navigation";
</script>

<section>
    <img src="/favicon.png" height="100" alt="vincoin_logo"/>
    <h1>VINCOIN</h1>
    <i>Modern currency for advanced mindset</i>

    <button on:click|self={() => goto("/learn-more")}>Learn More</button>
</section>

<style>
    section {
        height: 100vh;
        margin: 0;

        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        background: #80aed9;
        color: #dfdfdf;
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

    button {
        border: none;
        border-radius: 10px;
        padding: 0.65rem;
        margin: 10px;

        font-family: "Overpass", sans-serif;
        font-optical-sizing: auto;
    }

    button:hover {
        font-style: italic;
        font-weight: 300;
        color: rgb(0, 119, 79);
    }
</style>