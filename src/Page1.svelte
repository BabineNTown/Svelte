<script>
    import { fly } from 'svelte/transition'
    let y;
</script>

<svelte:window bind:scrollY={y}/>

{#if window}
    <main transition:fly="{{delay: 250, duration: 300, x: 100, y: 500, opacity: 0.5, }}" >
        <h1>
            Finally, connect Thunderbird to your Exchange email account at your office.
        </h1>

        <h2>
            You love <a class="Thunderbird" href="https://www.thunderbird.net/fr/" target="_blank">Thunderbird</a>. Your company uses Exchange.
            Owl is the little bird that lets the two talk to each other.
        </h2>
    </main>
{/if}

<style>
    main
    {
        margin-top: 12%;
    }
    h1
    {
        text-align: center;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
        font-size: 50px;
        margin-bottom: 20px;
    }
    h2
    {
        text-align: center;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
        font-size: 28px;
        opacity: 0.7;
    }
    a
    {
        text-decoration-style: dotted;
    }

</style>