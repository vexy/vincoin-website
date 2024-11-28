<main>
    <h1>VINCOIN</h1>
    <i>Modern currency for advanced mindset</i>

    <section>
        <a href="/learn-more">
            <img src="images/learn-more.svg" alt="learn_more" height="20"/>
            <span>Learn More</span>
        </a>
        <a href="https://github.com/vexy/vincoin">
            <img src="logos/github-mark.svg" alt="github_logo" height="20"/>
            <span>Source code</span>
        </a>
        <a href="https://discord.gg/dzbsT8jTg5">
            <img src="logos/discord-mark-blue.svg" alt="discord_logo" height="20"/>
            <span>Join our Discord</span>
        </a>
    </section>
</main>

<style>
    main {
        margin: 0;
        height: 100vh;

        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        background-image: url("/images/vincoin15.png");
        background-repeat: no-repeat;
        background-position: center;
        background-size: 100% 100%;
    }

    @media (min-width: 330px) {
        main {
            height: 100vh;
            background-repeat: no-repeat;
            background-position: center;
            background-size: 140% 80%;
        }
    }

    h1 {
        font-size: 3rem;
        text-align: center;
        margin: 10px;
    }

    i {
        margin-bottom: 15px;
    }

    a {
        border: none;
        border-radius: 10px;
        padding: 0.55rem;
        margin: 10px;
        background: #afaba9;
        color: rgb(81, 81, 81);

        display: flex;
        justify-content: center;
        align-items: center;
        gap: 5px;

        text-decoration: none;
    }

    a:hover {
        font-style: italic;
        font-weight: 300;
        scale: 0.95;
        color: rgb(26, 195, 139);
        background: rgb(54, 187, 142);
    }

    a:visited {
        color: rgb(81, 81, 81);
    }
</style>