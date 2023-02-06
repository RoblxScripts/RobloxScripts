<main>
    <h2>Loading</h2>
    {#if params && params.message}
        <p id="loadingmessage">Message is {params.message}</p>
    {/if}
</main>

<script>
    export let params = null
</script>